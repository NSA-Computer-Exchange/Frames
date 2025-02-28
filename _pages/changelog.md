---
layout: page
title: Changelog
include_in_header: true
---

# Changelog

<br>

### `Latest`
# **Version 1.2 Build 1**
This is the latest update to the Frames IOS app. These updates include various fixes to the SecondViewController (Emulator) page, updated product codes being sent to IDM in lowercase. Spoken prouct codes understood as one, two, three as oppsed to 1, 2, 3. etc.

#### What's New
- Changed product code number detection
- Removed spaces between words and numbers on spoken text for product codes.
- Updates to emulator screens for better clarity and more consist look/feel between frames and emulated view.

#### Bug Fixes
- Better product code detection
- Changed spoken product code to uppercase

<br>
________

<br>

# **Version 1.1 Build 2**
Introduced updates to voice commands as well as overall flow of the application. 2nd build deployed to TestFlight for developent testing.

<br>

## **Version 1.1 Build 1**
2nd deployment to App Store Connect. Introducing a new View Controller to act as an emulator view. This update provides the ability to show in an emulated view what is shown on the glasses.

#### What's New
- New Emulator UI View Controller
- Redesign of the initial (Main) ViewController page
- Removed function buttons

<br>

### `Initial Release`

## Version 1.0 Build 1
This is the initial IOS release pushed to App Store Connect in order to use TestFlight to test the code. Initial development was using python which ran on a notebook. In order to expand on the functionality and make it a more mobile/ hands free solution, the decision was made to build the app for IOS.

#### What's New
- Pair and communicate over bluetooth. Completely new Bluetooth stack
- Speech recognition using Apple Speech Recognition library
- Lua commands sent in REPL fashion to show instructions on the frames.
- Log viewer. Ability to toggle logs on or off.
- UIImage view to view captured image from the frames.
- Introduced new API code to get product information from ICSW in CSD over the SX api gateway.
- Introduced new API code to send captured image to Document Management to be used as product image. Image passed through 3rd party bg.remove api.

<br>
