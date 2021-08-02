# CV and Resume of Johannes Rave

Industrial designer, car modeller and former nightclub owner, now __Computer Science student__ and IT consultant.

A passionate coder and professional designer with logical thinking, I have a great willingness to learn, good communication skills and diverse work experience.

Recently I began working as an IT consultant at [INNOQ](https://www.innoq.com/en/).

## Formal documents and contact information

- Curriculum Vitae _[en](./documents/CV_johannesRave_EN.pdf)_ \| _[de](./documents/CV_johannesRave_DE.pdf)_
- Academic achievements _[en](./documents/210324_johannesRave_AcademicAchievement_EN.pdf)_ \| _[de](./documents/210324_johannesRave_Notenspiegel_DE.pdf)_
- [Email me](mailto:johannes.rave@gmail.com)

## Portfolio projects

### [drawingApp](https://github.com/johannesrave/drawingApp)

This desktop application was built in JavaFX as a student project. It has a DARK MODE, implemented with CSS.
  
![drawingApp demo](https://raw.githubusercontent.com/johannesrave/drawingApp/master/drawingApp_demo.gif)

### [splicer2D](https://github.com/johannesrave/splicer2D)

Splicer2D is an action-packed mobile game with a novel game-mechanism designed with Unity and written in C#.

![splicer2D](https://user-images.githubusercontent.com/31467653/110180080-6f2da580-7e09-11eb-9f53-6b7d64f11f0b.gif)  

## Scripting and automation

### [SparkAR](https://sparkar.facebook.com/ar-studio/)

This is a software package to create AR-filters for Instagram. Similarly to C# and Unity, it is possible to integrate TypeScript coding into the filters using the SparkAR-API. I work with this regularily to expand the possibilities of the studio-software, integrate game logic or debug existing problems with the young package. For example I did this:

- Integrated the physics engine cannon.js into projects, enabling forces, collisions and constraints for 3D-objects. (I am writing a little wrapper called "sparrow" to interface cannon with SparkAR.)

- Implemented billboarding on a tracked plane - an object will always face the user, even when the pane loses tracking and then "reappears".
  
  While the function itself is not very complex, it took some time to line up the quaternions correctly to make it happen. The documentation on the orientations of worldSpace, cameraSpace and planeTracking are patchy at best, but I got it to work eventually and published my solution to a relevant community. Before, the SparkAR-community had to abuse the particle-system to achieve this effect.

## Coding challenges and certificates

To better understand and contribute to work in the IT industry, I recently aquired my PSM I certificate:

[![My Professional Scrum Master I](./assets/psmi.png)](https://www.scrum.org/certificates/643511)

Besides my studies in Computer Science and Media, I have been learning and honing my skills on hackerrank, exercism and freecodecamp.

Have a look at my solutions to coding challenges here:

- [My 300h JavaScript-certificate](https://www.freecodecamp.org/certification/johannesrave/javascript-algorithms-and-data-structures) from [freecodecamp.org](freecodecamp.org)
- [My exercism profile](https://exercism.io/profiles/johannesrave)
- [My Java solutions](https://github.com/johannesrave/ExercismJavaTrack) for [exercism](https://exercism.io/)
- [My C# solutions](https://github.com/johannesrave/ExercismCSharpTrack) for [exercism](https://exercism.io/)
- [My hackerrank profile](https://www.hackerrank.com/johannes_rave)

### Generative Design

There are several node-based geometry packages in the industrial-design-space, but the most important one is Grasshopper, which ships with Rhino3D. Grasshopper can be used to generate repetitive geometry, recursive patterns and all kinds of interesting models and shapes. This can be achieved using nodes (__visual programming__), __Python__, and __C#__. I have worked with all of them, depending on the task at hand.

There is a bit of a learning curve, and professionals who master generating production-ready geometry are sought after, especially since the model has to incorporate minute design changes that only come up during the process. I built my models in a flexible way by separating concerns, to be able to include those design changes without having to begin from scratch on each iteration.

Unfortunately, I can't share images of these projects, as they were done for customers confidentially. I will still list them here to give an idea of the kind of task completed.

- Generative front grille with a custom curve-fitting function written in C#, inspired by my own work in the car industry. This might make it into a car for an Asian market.

- A shutline generator in for car-models, to automate the tedious process of building visual shutlines for presentations

- Recursive graphical patterns inspired by Muslim architecture

## Game-design and visual design

### [The Secret of Maike Island](https://www.adventuregamestudio.co.uk/site/games/game/2517-the-secret-of-maike-island/)

This is a classical point'n'click adventure game built in [Adventure Game Studio](https://www.adventuregamestudio.co.uk/) as a birthday present.

It deals with socio-economic pressures of the housing market in metropolitan clusters and destroying stuff with a bottle of prosecco.

![The Secret of Maike Island](https://user-images.githubusercontent.com/31467653/110179054-b87cf580-7e07-11eb-9700-16acd22ade5b.gif)  

### [Käpt'n Wildschwein](./captn_boar/)

I designed "Capt'n Boar" as a hero character for my nieces and nephews and modelled him in Blender. They sometimes send me drawings of him with his famous barrel of spaghetti.

![Capt'n Boar](./game_design/captn_boar/captn_boar_02.gif)

## Product-design and Automotive Modelling

- [Cars I have worked on](./product_design/README.md) as a 3D-modeller.  
  Customers included Audi, BMW and VW
- [Design portfolio 2014](./product_design/2014_portfolio_johannesRave_low.pdf)  
  My business-oriented product-design portfolio.
- [Design portfolio 2009](./product_design/2009_portfolio_johannesRave_low.pdf)  
  My more artistic product-design portfolio.

## Nightclub _wolf_

In 2012 I founded [_wolf_](https://www.facebook.com/wolfimbuch), a 600sqm nightclub in the cellar of a brewery in Pforzheim.  
It ran on great music, an honest amotsphere and a terrific staff of up to 16 people until January 2014.
The facebook page includes pictures of the location and events, and features the visual art style of our promotional material.

[This repo as a website](https://johannesrave.github.io) / [This website as a repo](https://github.com/johannesrave/johannesrave.github.io)
