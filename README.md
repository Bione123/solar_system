# solar_system

Project source can be downloaded from https://github.com/Bione123/solar_system/
-----------

Author & Contributor list
-----------
Fabio Pergami Feroldi

File list
-----------
```
./solar_system

README.md

solar_system.pde

Planet.pde
```
This is a simulation of a solar system made with processing.
Processing is a flexible software sketchbook and a language for learning how to code. It can be used both by beginners and experts to create visually oriented applications with an emphasis on animation and providing users immediate feedback through interaction.
It is open source and free to download, full of tutorials and reference pages.

Download Processing
---------

You can download it here: https://processing.org/download/

Setup
---------
Every processing project needs two functions: 
```
void setup(){

}
void draw(){

}
```
These are the two main functions, and then you're ready to code!

OOP - Object Oriented Programming
---------

Processing uses Java, which is powerful because of the OOP.

For the most part, OOP is advantageous because it allows you to re-use blocks of code without re-writing them.

I created a class "Planet" with some properties such as radius, distance from the sun, and angles, as well as methods, such as the constructor function that creates instances of the class, for example

```
class Planet {
 
 // some properties
  
  //constructor function
  Planet(float r, float d, float o){
    
    // some stuff
    
  }
  
  // other methods
  
  // creating instances of the class
  sun = new Planet(float r, float d, float o);
  
}
```
Then the sun spawns other planet that spawn their "children" or moons
If you're interested in OOP, start by watching this video: https://www.youtube.com/watch?v=8yjkWGRlUmY

# Useful sites

Image textures: http://planetpixelemporium.com
---------
Peasycam library: http://mrfeinberg.com/peasycam/
---------
Processing site and overview: https://processing.org/tutorials/overview/
---------
