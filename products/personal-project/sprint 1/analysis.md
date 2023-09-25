---
mainfont: PTSerif.ttf
sansfont: PTSans.ttf
monofont: PTMono.ttf
title:  'Chess App Analysis'
author: "Dylan Nas"
toc: true
include-before:
- '`\newpage{}`{=latex}'
---
\pagebreak

## Early Project Concept

A chess app that is connected to David's S6 project. The aim of the project is to improve the experience of the App with features that try to focus on several hardware features only mobile devices have. This will all be conceived by the Design thinking process. The app will have both an iOS and Android design, since it will be made in Flutter.

## Stakeholders

- Developers (David & Dylan)
- Teachers (David's side and Dylan's side with a focus on Dylan's side)
- People who like to play chess

## Base Features

To make sure my project is fully compatible with David's project, I will need to incorporate a few features to make that possible:

- Login that is equivalent to David's login system
- Play chess games against bots or other users (Online only)
- Add/Remove users as friends (Optional)

## Potential Technologies

- Wifi/Bluetooth for finding nearby players (to play a game or befriend in the application)
- Detecting shake for resetting the chess board after a game (or with dialog during one to cancel a match)
- Use Camera to detect physical chess board

## Potentional Feature Concepts

### Template

Viability: Low/Medium/High
Effort: Low/Medium/High
Engaging: Low/Medium/High
Concept:

### 1 Local finding of other players

#### Bluetooth

Viability: High
Effort: Low
Engaging: Medium
Concept: 
Allow people to find each other by broadcasting the phone as a Bluetooth beacon, which can make it possible to transfer small amounts of data.

#### Wi-Fi Direct

Viability: Low
Effort: High
Engaging: High
Concept: 
Allow people to find each other by using Wi-Fi Direct, which can make it possible to transfer larger amounts of data. This implementation has some problems since Apple and Android are not compatible with each other this way. (Apple doesn't actually use Wi-Fi Direct)

#### NFC

Viability: Low
Effort: Medium
Engaging: Low
Concept:
Allow people to touch their phones together to exchange data for the app. This would require both people to have the app open and choose to share their contacts/start a game.


### Reset gameboard by shaking device

### Scan physical chess boards with a camera