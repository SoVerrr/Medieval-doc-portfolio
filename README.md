Medieval Doctor is a game i've been working on with my friends since 12.2023. This repository serves as a presentation of mechanics and systems i've created for the game. 

The game's gameplay is about curing patients from various sicknesses with the premise of being able to do whatever you want to them. For example you can cut off on arm from someone who has a cold.

Prototype gameplay video: https://www.youtube.com/watch?v=XjgmXvPG714

Technologies used in the project:
- Unity
- C#
- Newtonsoft JSON
- Unity Events

List of mechanics/systems i've created/collaborated on:
- Patient system 
  - Sickness system
    
    ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/03ece599-a8ca-4fda-8f86-2f3e280c40c3)

  - Symptom system - adding and removing symptoms
 
    ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/e0d6b9f4-8dff-43b8-b2ea-8a5574c23903)


  - Dependencies system - checking if a certain symptom can be added or removed depending on other symptoms present/not present
 
    ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/8b0bc4e3-9d9e-4cc9-8c26-c402b659d218)

- Quest system

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/650c3bd6-c656-4256-ab79-fb47771890aa)

- File management system - built using Newtonsoft framework
- Upgrade system

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/6d616eb7-f3ea-4296-b502-b969da390469)

- Player interaction system - created using interfaces, events, and an overlapbox cast in front of the player which is shared by various systems present in the game.
- Picking up items/furniture with blueprints to put them down (collaborated)
- State machine used to transition between game states (Menu, loading screen, game, summary state)
- Walls fade'ing when they are obstructing player's view. (Present in the prototype gameplay video)

