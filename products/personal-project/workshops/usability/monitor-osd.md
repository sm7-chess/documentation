---
mainfont: PTSerif.ttf
sansfont: PTSans.ttf
monofont: PTMono.ttf
title:  'Usability Workshop'
subtitle: "Monitor OSD buttons"
author: "Dylan Nas"
toc: true
include-before:
- '`\newpage{}`{=latex}'
---
\pagebreak

## Problem
Computer monitors have a lot of different settings that need to be changed, these settings can be arranged and navigated in multiple different ways. The arrangement is seperate from the navigation, and needs to be explored seperate from each other. Different arrangements could not work with every kind of navigation however.

## Current Situation

There are multiple different Arrangments and Navigation styles

### Analysis Samsung OSD

Visibility  - Literally not visible, however the buttons when looked at or felt are quite intuitive (Up Down Left Right buttons, with OK in the middle)
Feedback    - Every single action causes a refresh and different state of the menu
Affordance  - It's very logical since it's a 2d interface with buttons that can move in every direction.
Mapping     - The interface resembles the control scheme to make it very easy to identify the right buttons for certain actions
Constraints - You only have 1 way of navigating through the interface, and can only move in 4 directions
Consistency - It's a very simple interface so consistency is quite apparent here, since not having consistency would just be weird.  vc 

### Arrangement

- Divided in categories that are listed out top to bottom
- Divided in categories that are listed out in a circle

### Navigation

- Joystick
- Linear button layout
- Joystick-like button layout
- Rotating dial

[Navigation](whiteboard_current_situation.jpg)

### Additional features

- Different hotkeys for going to certain (categories of) settings
- A home button to go back to the start of the settings
- Custom keys added on top of the basic keys, for launching certain functions (sometimes only for custom profiles)
- Remote version of the interface found on the monitor itself.

## Ideation

A few control methods I immediately will reject and that is the linear button layout and the Joystick-like button layout, since in my opinion these are very uncomfortable to control, but I understand their place since it's a low cost solution.

I came up with the following "optimal" control methods

- Rotating dial with top to bottom layout
	+ This will control well since you can control the position and confirm your selection all with the same dial, for a lot of settings you will never have to stop using the dial.
	+ A dial might be uncomfortable to click if it's in a downwards position.
	+ Not immediately apparent how to go right vs left/down vs up

- Rotating dial with circle layout
	+ This will control well since you can control the position and confirm your selection all with the same dial, for a lot of settings you will never have to stop using the dial.
	+ A dial might be uncomfortable to click if it's in a downwards position.
	+ Circle layout will be very intuitive with a dial, since it's the same shape and it's clear what direction you will move.
	
- Joystick with top to bottom layout
	+ This will be easy to understand, since all directions are directly apparent, same as with the dial you can navigate and change most of the settings without having to stop using the joystick.
	
- Joystick with circle layout
	+ Every direction of the stick will result in advancing to a menu or setting, making it quick to use once you know the locations of the settings you want to use
	+ Settings might be harder to find if the categorization is not of a high standard.

[Navigation](whiteboard_ideation.jpg)

## Primitive Prototype of Dial

[Prototype 1](physical_prototype_1.jpg)
[Prototype 2](physical_prototype_2.jpg)
[Prototype 3](physical_prototype_3.jpg)

## Usage in real world

After finding out that using a Dial for the OSD settings is actually a very old idea, that has been scrapped since it tends to have a lot of space usage that comes with it. I however think that my implementation would allow for a pretty smooth experience, as long as it is coupled with modern software, since the space constraints I believe are not really logical compared to having just 1 joystick or multiple capacitive buttons.


