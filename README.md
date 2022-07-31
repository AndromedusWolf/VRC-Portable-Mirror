# VRC Portable Mirror

## Overview
This is a portable mirror prefab that can plopped into your VRChat world. It is a simple object with a UI menu that allows the local player to bring a mirror anywhere around with them in the world. The mirror has three quality settings users can toggle between; High Quality, Low Quality, Transparent. There is also two sliders that will allow the local player to freely resize the width and height of the mirrors.

This is being made free to use by the community and you may alter and improve the package as you wish. All I ask is that, if you alter the package and wish to distribute it, that you do so freely. There is no need to credit me, you may do so if you wish however. What I would appreciate is if you leave the link to this package on the UI panel so that other people know where it was downloaded.


## Dependencies

It is VERY important that you have the following two packages downloaded already before downloading this package! The Portable Mirror will not work without them!

1. You will need [Udonsharp](https://github.com/vrchat-community/UdonSharp)

2. You will need [VRCPlayersOnlyMirror](https://github.com/acertainbluecat/VRCPlayersOnlyMirror)


## Set-Up

1. Ensure you have imported both UdonSharp and VRCPlayersOnlyMirror packages into your Project window

2. Download and import the VRC Portable Mirror package into your Project window

3. Go into the Portable Mirror folder and drag the prefab into the scene. Tada! That's all you need to do! Your portable mirror should be ready to go!

![Desktop Screenshot 2022 07 29 - 18 16 24 45](https://user-images.githubusercontent.com/99851805/181853264-6a1e854e-37c6-4ba1-b913-215f413f7649.jpg)


## Modifications

The mirror respawn button included in the prefab is a very simple and basic one. If you do not wish to use this, but rather your own, follow these steps below:

1. If your button does not have a collider, add one.

2. Add an Udon Behaviour to your button.

3. Navigate to the "Scripts" folder and drag the "ResetMirror" U# Script into the Udon Behaviour field.

![Desktop Screenshot 2022 07 29 - 18 44 00 05](https://user-images.githubusercontent.com/99851805/181854955-9bbbace7-e690-4fb0-952a-5d3a2c10544f.jpg)

4. Follow the diagram below to know what to put where.

![Desktop Screenshot 2022 07 30 - 22 57 53 59](https://user-images.githubusercontent.com/99851805/182036842-e6f2ed44-3221-4bfe-a69f-ac1baed12c70.jpg)

Congrats! You should hopefully now have a functional reset/respawn button.
