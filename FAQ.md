# Frequently Asked Questions

## Resolution/Display Issues
Most of the CSS is not responsive or scaled for displays. Instead it is using static sizes. To overcome any display issues, please use the browser zoom in/out settings to ensure proper display resolution.


## Clicks not responsive or lagging
This happens after performing a spin or guessing a vowel. A large text will appear showing your points in Green or Red and it will fade in for 5 seconds and then fade out after 5 seconds. The problem is, nothing is clickable until the text is fully faded out, which gives the appearance of lagging.
This fade timeout can be edited in the Javascript to your liking. Or it might be possible to change the Z-index so that the gameboard is still in foreground, even if the popup is fading in/out.


## Clicking SPIN multiple times
Dont do that! weird things happen.
