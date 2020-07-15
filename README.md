# Blurred Reality
VR headset using a rapidly oscillating lens setup to provide depth cues

## The Idea
It is going to use a rapidly oscillating lens setup to continuously change the focal length, displaying the corresponding parts of the image at the right time.

## Problems
- **refresh rate**: 50Hz display can only display f.e. 50 depth layers per second (->1FPS)
- **lens setup**: might be too noisy/make the headset vibrate too much

## Potential Solutions
- **refresh rate**: replace backlight by high-speed HDR backlight (LED matrix) since the actual image doesn't need to change for the individual depth layers
- **lens setup**: use varifocal lens
