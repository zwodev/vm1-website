---
hide:
    - footer
---

# VM-1 features

during many moments of brainstorming we came up with tons of features that would be awesome for the VM-1. we would like to list all of them here - to inspire you as well. not all of them are implemented. some of them will be in the future. do you have any more ideas? contact us.

## current features
* <mark>low latency hdmi input</mark> with 30fps
* <mark>two (independent) hdmi outputs</mark>
* load up to <mark>64 videos</mark> to the provided media-slots (four banks with 16 mediaslots each; the total amount of videos is limited by the storage of your raspberry pi)
* simultaneous <mark>playback of up to four videos</mark>
* <mark>fading</mark> and mixing of videos and live-cameras
* all video signals are handled in <mark>full hd</mark> (1080p)
* switching between media input via keyboard:
    * use any <mark>external keyboard</mark> for a quick-start
    * or use the <mark>VM-1 controller</mark> for more comfort
* upload videos wirelessly via the app <mark>[local send](https://localsend.org)</mark>
* adjust the <mark>fade time</mark> when switching between media sources
* save all <mark>settings</mark>
* videos are <mark>looping</mark> by default
* <mark>oled screen</mark> to control the VM-1

## planned features

for the next release (july 2025) we would like to implement:

* the second hdmi input
* video effects (like chroma key)
* programmable shaders
* wireless camera stream from smartphones
* recording video loops
* video editing features (set in- and out-point)
* homographic projection mapping (via effect shader)
* playback auf audio from the video
* media manager to sort all your files with tags
* filename, current timecode of video, video-duration on oled display
* preview video thumbnail on oled display

## more ideas

for further releases, this is an open list of ideas:

* *"infinite view workflow"*. right now, the video-sources are limited to two fullscreen hdmi outputs. the goal would be to have one big video output across both screens and place (transform, scale, rotate, mask) the videos freely on the canvas.
* autoplay videos when starting the VM-1 (useful for media art installations)
* copy files from usb-drive
* change playback speed and playback direction
* use an audiofile as media input
* use an image as media input
* an app to control the vm-1
* add webcams as video source
* control via osc and midi
* cv (control voltage) input to connect VM-1 to a modular synthesizer
* syncing the video of multiple VM-1 in a network
* automatically sequence through the media slots (like a drum sequencer)

