# Cyber Spy

## Elevator Pitch

Cyber Spy is an educational puzzle game with a dramatic storyline attached. Cyber Spy will introduce players to basic bash commands through a time based environment. The story follows a hacker, and his companion Alfred, through several missions to dethrone a corrupt organization. Players should be able to traverse through the terminal efficiently with the knowledge gained after completing this game.

## Influences (Brief)

- Super Mario World:
  - Medium: Game
  - Explanation: *We plan to mimic the style of super mario world and the pixel art. The movement in between levels will resemble the movement of a platformer like mario*
- Hacknet (https://en.wikipedia.org/wiki/Hacknet):
  - Medium: Game
  - Explanation: Much like our planned game, Hacknet is a hacking-based puzzle game in which the majority of gameplay comes in the form of typing commands in a Unix-like terminal. The main goal in Hacknet is to ‘hack’ into other computer systems, steal imaginary files, and acquire superuser privileges. It incorporates gameplay aspects like memory management (you can only run a certain amount of programs before you run out of memory) and a timer later on in the game to make doing so more difficult. We plan on taking inspiration from the terminal design, as well as aspects like the timer.
- Mission Impossible
  - Medium: Movie
  - Explanation: *We plan on creating a mission based game where the user must break into a facility (directory) using terminal commands. There will also be a time constraint. There will also be a butler/narrator character, much like the tech team in Mission impossible, that will guide you through your mission, providing hints and instructions as needed.*

## Core Gameplay Mechanics (Brief)

*Give a very high-level description of any core gameplay mechanics*

- *Typing commands into terminal to perform actions*
- *2D Navigation Throughout the facility*
- *Item Collection within your inventory*
- *Display success screen after completing a mission*
- *Display defeat screen after failing a mission*

# Learning Aspects

## Learning Domains

Introductory Systems Programming

## Target Audiences

*Incoming freshmen in college pursuing a computer science degree. Specifically students learning how to use bash commands.*

## Target Contexts

*This could be used as an introductory assignment for CISC210. Students looking to practice their skills in the terminal can also play this game in their free time.*

## Learning Objectives

After playing Cyber Spy, students should be able to traverse the terminal using the command line efficiently.

- *Short Name*: *Formal Learning Objective #1*
- *Short Name*: *Formal Learning Objective #2*
- *Short Name*: *Formal Learning Objective #3*

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- Players should know how to type a minimum of 30 wpm
- Players should know that commands can cause their computer to perform actions

## Assessment Measures

*Describe how the learning will be assessed, e.g., pre/post multiple-choice test, or SAT, or some other instrument.*

*If proposing a new instrument, briefly and concisely list some example assessment questions.*

Given a directory name, utilize bash commands to access it.
Given a file name, utilize bash commands to delete it.
Given a file name, utilize bash commands to move it to another directory.

# What sets this project apart?

- Most coding assessments that introduce students to the terminal don't intend to be entertaining, but our game will have fun graphics, an engaging story, and thrilling gameplay.

*Give some reasons why this game is not like every other game out there. Whether the learning objective is unique, the gameplay mechanics are new, or what. You should persuade the reader that your game is novel and worthy of development. Consider arguments that would be persuasive to a Venture Capitalist, Teacher, or Researcher. These might be focused on learning needs, too.*

- *Reason #1*
- *Reason #2*
- *Reason #3*
- *Reason #4*
- *etc.*

# Player Interaction Patterns and Modes

## Player Interaction Pattern

*Describe how people play your game, how many players are involved at once, how they interact with the system works, etc.*

This is a single player game. The player will interact with the via typing keyboard inputs, moving with arrows, and clicking on menu buttons when needed.

## Player Modes

*Your game has one or more player modes. Describe each discrete mode, considering things like menus too. Generally describe the transitions between modes too.*

- Single-player: You repeatedly complete missions to advance through the story.

# Gameplay Objectives

- Reach the end of the mission:
    - Description: Do what the prompt at the top of the screen requests
    - Alignment: This aligns with our learning objective because it forces players to hone the skills they've learned and will help them memorize commands after repeated use.
- Complete all missions to finish the game:
    - Description: Traverse through each mission by accomplishing their respective goals
    - Alignment: Each mission will establish a new topic for the player to learn. Each topic will build upon each other, and by the end players will know what each command does and when to use them.

# Procedures/Actions

*Describe the control scheme and what actions a user can take in the game.*

You can type when a command line is shown, and enter these commands. In between missions you can move around using arrow keys, and press a button to start mission.

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

- If the player enters an invalid command, they will get an error and hint
- If the player enters a valid command, it will work and they will advance through the current mission
- They will have a toolset of commands available to them to reference and utilize
- The list of commands that they will learn through the missions are as follows:
ls
cd
rm
touch
cat
mv
mkdir
cp

# Objects/Entities

*What other things are in the world that you need to design? These may or may not directly translate to actual objects and classes.*

- There is a text input for users to type into
- There is a command line that user input is displayed when entered
- There is a prompt
- There is a main character to control in between missions
- There is a companion character that will speak to you during missions
- There is a timer during missions



## Core Gameplay Mechanics (Detailed)

- *Typing commands into your “terminal”*: *The majority of game interaction will be through the user typing a correct command sequence for the current mission into their terminal. Assuming the user types correctly, this will be how they traverse through tasks and levels.*
- *Core Gameplay Mechanic #2*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #3*: *Describe in 2 paragraphs or less, along with how it generally works*

    
## Feedback

*Explicitly describe what visual/audio/animation indicators there are that give players feedback on their progress towards their gameplay objectives (and ideally the learning objectives).*

*Describe what longer-term feedback you detect and give that guides the player in their learning and lets them know how they are doing in regards to the learning objectives.*

If a command is wrong, your companion will tell you it is wrong and give you a hint in the right direction. Text on the screen shows if a command worked or did not work. 

# Story and Gameplay

## Presentation of Rules

*Players have a virtual assistant like Alfred is to Batman. Alfred will introduce your mission, tasks, and give you your tools (ls, cd, touch, etc.) as they become needed*

## Presentation of Content

*Players will slowly be given tools as mentioned before, and expected to use them at least one time before being given a different tool by alfred, e.g. Alfred: “You’re gonna need a wrench to break that glass. Use ls to view your backpack items, including the wrench I just gave you.”*
## Story (Brief)

*The Summary or TL;DR version of below*

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

![alttext](Storyboard.jpg)

# Assets Needed

## Aethestics

*Give a sense of the aesthetics of your game, the spirit and atmosphere. Use descriptive, evocative words that can help the reader understand the emotional response of your game.*

## Graphical

- Characters List
  - *Characters 1*
  - *Characters 2*
  - *...*
- Textures:
  - *Texture 1*
  - *Texture 2*
  - *...*
- Environment Art/Textures:
  - *Environment Texture 1*
  - *Environment Texture 2*
  - *...*


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - *Game region/phase/time*: *Example 1*, *Example 2*
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - *Game Interaction*: *Example 1*, *Example 2*
  - *Game Interaction*: *Example 3*, *Example 4*


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3


