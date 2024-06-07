Medieval Doctor is a game i've been working on with my friends since 12.2023. This repository serves as a presentation of mechanics and systems i've created for the game. 

The game's gameplay is about curing patients from various sicknesses with the premise of being able to do whatever you want to them. For example you can cut off on arm from someone who has a cold.

Prototype gameplay video: https://www.youtube.com/watch?v=XjgmXvPG714

Technologies used in the project:
- Unity
- C#
- Newtonsoft JSON
- Unity Events
- New input system

List of mechanics/systems i've created/collaborated on:
- Patient system 
  - Sickness system
    
    ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/03ece599-a8ca-4fda-8f86-2f3e280c40c3)

  - Symptom system - adding and removing symptoms
 
    ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/e0d6b9f4-8dff-43b8-b2ea-8a5574c23903)


  - Dependencies system - checking if a certain symptom can be added or removed depending on other symptoms present/not present
 
    ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/8b0bc4e3-9d9e-4cc9-8c26-c402b659d218)
  - Symptom handling - Player can add and remove symptoms from the patient using tools, the system checks for dependencies and if the symptom can be added/removed
  - Patient release - When the player decides that the patient is cured, they can press a button to release them and get a varying amount of points and money depending on how many symptoms they cured/caused

- Quest system

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/650c3bd6-c656-4256-ab79-fb47771890aa)

- File management system - built using Newtonsoft framework
- Patient card - Interactable UI element that shows Patient's name, story and symptoms. It also allows the player to release them from the hospital

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/2d650b05-d606-4f3a-abbe-5b7100d29d2e)

- Upgrade system - System used to spawn rooms with various tools and furniture elements. Created with scriptable objects for easier design, it also has a spawn requirement system built in. 

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/6d616eb7-f3ea-4296-b502-b969da390469)

- Player interaction system - created using interfaces, events, and an overlapbox cast in front of the player which is shared by various systems present in the game.
- Meta-knowledge notebook - Notebook that shows sicknesses and tools that have been discovered by the player so far
  

https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/0bf937fc-535b-4eed-ba7b-44c109d16758


- Picking up items/furniture with blueprints to put them down (collaborated)
- Tools - A tool can be used by the player to Add/Remove/Check for symptoms, a tool can be "One use" which means that it gets destroyed after the player uses it on a patient

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/6bb1de36-d5c7-440d-a0de-d8ec371d089d)
- Crafting system - the player can use ingredients from the chests to craft various recipes in multiple crafting tables

  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/8ba689fd-247b-424c-9484-7e1ca2be368c)  ![image](https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/415a403a-0fee-41c6-b70d-3296d0258720)
  

https://github.com/SoVerrr/Medieval-doc-portfolio/assets/82769474/4eaadf62-b995-4cd3-a0f2-24eeb23b234f




- State machine used to transition between game states (Menu, loading screen, game, summary state)
- Walls fade'ing when they are obstructing player's view. (Present in the prototype gameplay video)

