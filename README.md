# AACompliantColourPalette
Used to easily create AA compliant colour swatches of 3-16 colours, with tools to help create colours that are distinct from eachother, as well as able to load hex codes to see existing colours 

# How It Works
# Generated Palette
The app creates a palette by stepping through hue values across a configurable spread. Saturation and lightness are varied slightly to create a more visually balanced set of swatches.

# Accessibility Checking
Each colour is tested against the selected background colour using contrast ratio calculations based on relative luminance.

# Forced Compliance
When AA or AAA mode is selected, the app adjusts lightness values until the target contrast ratio is met whenever possible.
