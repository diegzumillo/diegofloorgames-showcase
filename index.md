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

#A ray marcher renderer
Although this is running in the Godot game engine, the renderer itself is coded from scratch inside a fragment shader. The goal of this project is to eventually make a flight simulator in a scifi setting; then the Godot engine will start becoming more relevant in this project, as I add functionalities unrelated to the renderer. For now it is just a renderer with basic features: full planet scale terrain, pre-defined number of dynamic lights with smooth shadows, a number of basic SDF (signed distance function) to combine into complex objects, including fractals, basic material with specular, color and displacement. 

![Image](https://imgur.com/IgW0V8h.png)

![Image](https://imgur.com/ttg0F4a.gif)

![Image](https://imgur.com/K2bbrct.png)

![Image](https://imgur.com/eu7GGJm.png)

![Image](https://imgur.com/2einiuE.gif)

![Image](https://imgur.com/tmawcqx.gif)

![Image](https://imgur.com/uiSlEAb.gif)


links
stealth proto https://youtu.be/3hU832U6Rao
ropes https://youtu.be/_eehUli9B-4
sound https://youtu.be/g29Gz-cF9yI
flightsim https://youtu.be/1g1bmk2ZKRo
pico https://youtu.be/Uxl1X4Zmlf4
sprite https://youtu.be/EuBdXLUwYdw
daw https://youtu.be/eyyy4n1sTiw
