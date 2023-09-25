---
mainfont: PTSerif.ttf
sansfont: PTSans.ttf
monofont: PTMono.ttf
title:  'Chess App Case'
author: "Dylan Nas"
toc: true
include-before:
- '`\newpage{}`{=latex}'
---
\pagebreak

## Problem definition

The chess app project is aimed at using innovative technologies to improve the way we play chess on our phones. It is supposed to connect to David's backend, but this will not be necessary for me to get a proper working app.

## Opportunities

- Location based chess: Use GPS capabilities to enable location-based chess matches, allowing players to challenge opponents in their vicinity.
- Physical to virtual conversion: Enable the app to recognise physical chess boards and pieces through the smartphone camera, offering opportunities for real-world interaction.
- Multiplayer on the Go: Facilitate quick and easy multiplayer chess matches by leveraging mobile connectivity and peer-to-peer networking.
- Sensors: Incorporate device sensors (accelerometer, gyroscope) for interactive and dynamic chess experiences, such as tilting the phone to adjust the board's perspective.

## Research questions

1. How does the inclusion of local finding of users increase the quality of chess games player?
-  Criterion: An increase of 2 on a scale of 10 when asked to rate a chess game when initiated locally.
2. How does a quick start feature impact amount of chess games started?
-  Criterion: A statistically meaningful rise in the amount of chess games started by users who get the feature.
3. Does having a seperate interface for both iOS and Android improve satisfaction among users?
-  Criterion: An increase of 2 on a scale of 10 when showing an user a design tailored to their platform.

## Goals
1. Streamline the user interface to make sure new people (after installing) can start a chess game in ~30 seconds.
2. Available in Dutch and English to increase the amount of people that can use the application
3. Produce 2 features that improve the "barrier of entry" of a chess game according to 50% of testers that don't play chess regularly.

## Stakeholders

- Development Team (David and Dylan)
- Teachers (Mostly Erik/Ruud)
- People who enjoy playing chess (in varying degrees)

## Approach

I will probably single out 1 or 2 very promising technologies and use this as the main features of the app.
I want to use a hybrid approach where I create a M3 (Material 3) based design for android and a HIG (Human Interface Guidelines) based design for iOS. Where I will put a focus on the iOS design if there is any shortage of time.

## Do's

- Prioritise user-friendliness and accessibility in UX
- Create a balance between features for users of different experience levels.
- Lower the barrier of entry for playing a chess game.

## Don't's

- Keep it simple, don't make too many features
- Ensure the app enhances the chess experience rather than replacing it entirely.
- Hardware usage should be seamless, prevent bloat in the UX.