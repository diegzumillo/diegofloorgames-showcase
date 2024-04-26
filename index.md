
* auto-gen TOC:
{:toc}


# Game in Unity - Apple & Worm: Patching holes on spacetime
## A showcase of the technical achievements of this project

Apple & Worm is a platformer that happens in a curved 2D space, where different regions connect to other regions in unintuitive ways. This creates a game space with non trivial topology. While the game itself is still in development the engine is done. 

In order to achieve the curved and interconnected space the game design requires, several approaches were implemented and tested. Here you can see some images of the progress of the engine at its various stages.

### A video on Youtube showcasing the gameplay
[![Gameplay video](https://img.youtube.com/vi/G-1nO81KK1M/0.jpg)](https://www.youtube.com/watch?v=G-1nO81KK1M)

### Early tests of curved spaces

![Image](https://imgur.com/RKGGOYb.gif)

![Image](https://imgur.com/0QfeMET.gif)

![Image](https://imgur.com/x3PdqZC.gif)

And the first iteration of a custom physics engine using Verlet integration method.

![Image](https://imgur.com/kyEd4GZ.gif)

The new implementation (but still using the custom physics engine)

![Image](https://imgur.com/yBcefAv.gif)

### Custom editor extensions

![Image](https://imgur.com/QKB8N1m.gif)

![Image](https://imgur.com/N2fTUmJ.gif)

![Image](https://imgur.com/PtXbgeL.gif)

# A ray marcher renderer in a custom engine in C

This project started its life as a quick experiment in Unity. I wanted to write a ray marcher in shader. It worked, but it felt like I was fighting against the engine. So I moved to Godot, and it felt the same. This project is one of those rare cases where building an engine from the ground up makes sense. The communication with the shader needs to be hand crafted to make this work as intended, and that's what I did.
The goal of this project is to eventually make a flight simulator in a scifi setting; A few basic features already implemented: full planet scale terrain, pre-defined number of dynamic lights with smooth shadows, a number of primitive SDF (signed distance function) to combine into complex objects, including fractals, basic material with specular, color, texture, and displacement. The whole engine is put together with SDL2 and openGL.

![Image](https://imgur.com/IgW0V8h.png)

![Image](https://imgur.com/ttg0F4a.gif)

![Image](https://imgur.com/K2bbrct.png)

![Image](https://imgur.com/eu7GGJm.png)

![Image](https://imgur.com/2einiuE.gif)

![Image](https://imgur.com/tmawcqx.gif)

![Image](https://imgur.com/uiSlEAb.gif)


# Game for the Mega Drive
SGDK is a library for C that allows one to program the SEGA Mega Drive. I always wanted to make a Mega Drive game, but was never insane enough to code in ASM, so this came in handy! It's still extremely low level coding, very close to the hardware. It was a nice challenge and learning project. I eventually shelved this project because I wasn't too happy with the prototype, but has since been revived for an upcoming kickstarter campaign.

Initially, this was going to be closer to games like Prince of Persia, Flashback, Blackthorne etc, but with stealth

![Image](https://imgur.com/Zn9igXd.gif)

Testing guard behavior:

![Image](https://imgur.com/vR3jdtg.gif)

Testing level transition

![Image](https://imgur.com/i9ea6vr.gif)

Once that wasn't working for me I decided to implement a more free form movement style

![Image](https://imgur.com/qLosX49.gif)


Extra artistic stuff:
![Image](https://imgur.com/T3W1Cbp.png)
![Image](https://imgur.com/fuz1sAx.gif)
![Image](https://imgur.com/Ivdk1u2.png)

# Assorted videos of old projects

## A stealth game prototype. 
It has parkour movement implemented, (with a damn cool grapple system I still want to use somehwere) as well as a novel detection system that analyzes a guard's actual vision for changes.

[![Gameplay video](https://img.youtube.com/vi/3hU832U6Rao/0.jpg)](https://www.youtube.com/watch?v=3hU832U6Rao)

## Old 3D puzzle platformer
Very old. Looks fun though.

[![Gameplay video](https://img.youtube.com/vi/_eehUli9B-4/0.jpg)](https://www.youtube.com/watch?v=_eehUli9B-4)

## Sound propagation system
I'm pretty sure this was meant to go with the stealth prototype.

[![Gameplay video](https://img.youtube.com/vi/g29Gz-cF9yI/0.jpg)](https://www.youtube.com/watch?v=g29Gz-cF9yI)

## Basic Flight simulator dynamics
Yes, this is for the ray marcher project above. I made this as a proof of concept and it will definitely make its way to the ray marcher eventually. The plots show some of the flight dynamic coefficients changing in real time. This was made in Unity.

[![Gameplay video](https://img.youtube.com/vi/1g1bmk2ZKRo/0.jpg)](https://www.youtube.com/watch?v=1g1bmk2ZKRo)

## A simple game on Pico-8

[![Gameplay video](https://img.youtube.com/vi/Uxl1X4Zmlf4/0.jpg)](https://www.youtube.com/watch?v=Uxl1X4Zmlf4)

## A sprite tool
For the Mega Drive game project I saw the need to make this tool. It shifts the sprite each frame and outputs all the offsets. This was made in Godot.

[![Gameplay video](https://img.youtube.com/vi/EuBdXLUwYdw/0.jpg)](https://www.youtube.com/watch?v=EuBdXLUwYdw)

## A music maker
Never finished it but the idea was to make a basic note sequencer. Also made in Godot.

[![Gameplay video](https://img.youtube.com/vi/eyyy4n1sTiw/0.jpg)](https://www.youtube.com/watch?v=eyyy4n1sTiw)
