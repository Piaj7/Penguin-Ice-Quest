# Penguin-Ice-Quest
Penguin Ice Quest is a 2D side-scrolling platform game in which the player controls a penguin navigating through icy environments. The aim of the game is to collect fish, avoid enemies, and reach the end of each level. The project was developed as part of a Software Development module during my second year at the University of Hertfordshire. It demonstrates practical skills in game design, programming, testing, and project management.

## Table of Contents:
1. [Project Overview](#1-project-overview)
2. [Breakdown](#2-breakdown)
3. [Target Audience](#3-target-audience)
4. [User Profiles](#4-user-profiles)
5. [User Requirements](#5-user-requirements)
6. [System Requirements](#6-system-requirements)
7. [Game Rules & Mechanics](#7-game-rules--mechanics)
8. [Development Strategy](#8-development-strategy)
9. [Scrum Backlog](#9-scrum-backlog)
10. [Design & Storyboard Mock-ups](#10-design--storyboard-mock-ups)
11. [Development Log](#11-development-log)
12. [Testing](#12-testing)
13. [References](#13-references)
14. [Evaluation](#14-evaluation)
   
## 1. Project Overview
Penguin Ice Quest is a 2D side-scrolling platform game in which the player controls a penguin navigating through icy environments. The aim of the game is to collect fish, avoid enemies, and minimise damage while progressing to the end of each level.

The player begins with three lives and must collect a required number of fish to unlock new levels. As the game progresses, levels increase in difficulty, introducing new challenges and obstacles.

The game concept was inspired by the mobile platform game Lep’s World. While inspired by Lep’s World, Penguin Ice Quest features original characters, environments, and gameplay mechanics

## 2. Breakdown
This project was developed individually. All stages of development, including planning, implementation, testing, documentation, and evaluation, were completed independently.

## 3. Target Audience
### Primary Target Audience:
The primary target audience for Penguin Ice Quest is casual gamers aged 4 and above who enjoy 2D side-scrolling platform games similar to classic titles such as Mario.

The game is designed to be:
- Easy to learn and understand
- Suitable for short, casual play sessions
- Replayable, encouraging players to collect fish in order to progress to the next level
- Accessible for all skill levels
- Enjoyable for more experienced players

## 4. User Profiles
### User Profile 1
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/ab70bdc2-d6e6-4f59-86d3-65458ad82a33" />

### User Profile 2
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/dd116292-daa7-47bf-bd0a-dca69647ed4b" />


## 5. User Requirements
Users MUST be able to:
- Move left and right using keyboard controls
- Jump to reach platforms and avoid obstacles
- Collect fish pickups during gameplay
- Lose a life when colliding with an enemy or hazard
- Unlock and access the next level after collecting the required number of fish
- View the current number of lives remaining on the UI
- Restart the level after losing all lives
- Pause or quit back to the main menu

## 6. System Requirements
### Functional Requirements
The system must:
- Support player movement (left/right) and jumping using keyboard input
- Detect collisions between the player, platforms, enemies, hazards, and collectibles
- Increase the fish counter when a fish collectible is collected
- Decrease the player’s lives when the player collides with an enemy or hazard
- Trigger a Game Over state when the player’s lives reach zero
- Provide the player with the option to:
- Restart the current level
- Return to the main menu
- Trigger a level completion state when the player reaches the end of the level
- Unlock the next level when the required number of fish has been collected
- Display the fish counter and remaining lives on-screen during gameplay

### Non-Functional Requirements
The system should:
- Run smoothly with responsive controls and minimal input delay
- Maintain stable performance without crashes during gameplay
- Provide a clear and readable user interface
- Be structured using modular and organised Blueprints for maintainability
- Be scalable to allow future additions such as new levels or enemies

## 7. Game Rules & Mechanics
- The player begins each level with three lives.
- The player can move left and right and jump to navigate platforms.
- Fish collectibles are placed throughout the level and increase the player’s total fish count when collected.
- If the player collides with an enemy or hazard, one life is lost.
- When all lives are lost, the game enters a 'Game Over' state, where the player can choose to restart the level or return to the main menu.
- The level is completed when the player reaches the end goal area.
- A required number of fish must be collected to unlock the next level.
- Each new level may introduce increased difficulty, such as more enemies or more complex platform layouts.

## 8. Development Strategy
This software development project was developed using an Agile Scrum-based methodology. The whole development process was decomposed into short, manageable time periods called sprints. Each sprint focused on implementing and testing specific features of the game.

A product backlog was made at the start of the project to list all required features and tasks. These tasks were ordered based on importance and development difficulty. During each sprint, selected backlog items were implemented, tested, and reviewed.

Progress was monitored using weekly development logs and backlog reviews. Completed features were evaluated, and any issues were identified and resolved before progressing.

GitHub was used for regular commits and backups throughout development. This helped to track changes and reduce the risk of any work getting lost or corrupt.

### Advantages
The use of an Agile approach allowed flexibility during development, enabling features to be improved or adjusted based on testing results and time constraints.

### Disadvantages
Planning and reviewing sprints alone required strong self-discipline and time management. Some features had to be simplified or postponed due to limited development time within each sprint. Maintaining detailed documentation alongside development was time-consuming because I was developing alone.
## 9. Scrum Backlog
| ID | Feature / Task      | Priority | Status        | Test Method                        |
| -- | ------------------- | -------- | ------------- | ---------------------------------- |
| 1  | Project setup       | High     | Complete      | Project opens without errors       |
| 2  | Player movement     | High     | Complete      | Character moves smoothly           |
| 3  | Jump system         | High     | Complete      | Player can clear small gaps        |
| 4  | Camera follow       | High     | Complete      | Camera follows player correctly    |
| 5  | Level 1 design      | High     | Complete      | Level loads and is playable        |
| 6  | Fish collectibles   | High     | In Progress   | Fish increases score on collection |
| 7  | UI (lives & score)  | High     | Planned       | UI updates correctly               |
| 8  | Enemy AI            | Medium   | Planned       | Enemy damages player on contact    |
| 9  | Life system         | Medium   | Planned       | Lives decrease correctly           |
| 10 | Game Over screen    | Medium   | Planned       | Restart/menu options work          |
| 11 | Level progression   | Medium   | Planned       | Next level unlocks correctly       |
| 12 | Main menu           | Low      | Planned       | Menu navigates correctly           |
| 13 | Sound effects       | Low      | Planned       | Sounds play at correct events      |
| 14 | Bug fixing & polish | High     | In Progress   | No major bugs remain               |
| 15 | Final testing       | High     | Planned       | All tests pass                     |



## 10. Design & Storyboard Mock-ups
The visual design of Penguin Ice Quest follows an ice-themed style, using a blue and white colour palette to represent frozen environments. Levels take place in snowy landscapes, icy platforms, and frozen caves, helping to maintain visual consistency throughout the game.

The main character is a cartoon-style penguin designed to be easily recognisable and appealing to players of all ages. Enemies are also created in a simple, animated style to match the overall theme and tone of the game.

Each level is structured to gradually introduce new challenges, such as moving platforms, gaps over water, and enemy patrols. Early levels act as tutorials, while later stages increase in difficulty through more complex layouts and obstacles.

The user interface is minimal and easy to understand. The player’s remaining lives and fish count are displayed on-screen at all times to provide continuous feedback.

### Storyboard Flow

1. The game begins at the main menu, where the player can start a new game or exit.
2. The player is placed at the beginning of a level in an icy environment.
3. The player navigates platforms, avoids enemies, and collects fish.
4. If all lives are lost, a Game Over screen appears with options to restart or return to the menu.
5. When the player reaches the level exit, the level is completed.
6. If enough fish have been collected, the next level is unlocked.
7. The player progresses through increasingly challenging levels until the final stage is completed.

Design mock-ups, level sketches, and in-game screenshots will be added as development progresses.

## 11. Development Log
### Week 1 - Project Setup & Planning
#### Date: W/C 16 February 2026
#### Completed:
- Created GitHub repository
- Structured README file
- Sections 1-8 of README completed
- Planned initial Scrum backlog
- Set up Unreal Engine Project
- Implemented basic player movement

#### Planned for Next Week:
- Improved player movement responsiveness
- Adjusted jump physics
  
#### Problems / Barriers
- Time constraints
  
### Week 2 - Core Gameplay Development
#### Completed:
- Improved player movement responsiveness
- Adjusted jump physics
- Created basic level layout with platforms

#### Planned for Next Week:
- Add fish collectibles
- Begin UI implementation

#### Problems / Barriers:
- Movement initially felt too fast and unrealistic

---

### Week 3 - Level & Mechanics
#### Completed:
- Refined level layout
- Tested platform collisions
- Began planning collectible system

#### Planned for Next Week:
- Implement fish collection system
- Start UI display

#### Problems / Barriers:
- Collision inconsistencies at platform edges

---

### Week 4 - Testing & Improvements
#### Completed:
- Tested gameplay mechanics
- Improved level design
- Reviewed backlog progress

#### Planned for Next Week:
- Implement lives system
- Add Game Over functionality

#### Problems / Barriers:
- Time management balancing development and documentation

## 12. Testing


### Test Plan

### Test Log
| Test ID | Test Description        | Steps                          | Expected Result                          | Actual Result                  |
| ------: | ---------------------- | ------------------------------ | ---------------------------------------- | ------------------------------ |
| T1      | Player movement        | Press left/right keys          | Player moves smoothly                    | Movement works correctly       |
| T2      | Jump system            | Press jump key                 | Player jumps and lands on platform       | Jump works correctly           |
| T3      | Platform collision     | Land on platform               | Player does not fall through             | Collision works                |
| T4      | Edge detection         | Walk to edge of platform       | Player stops correctly                   | Works as expected              |
| T5      | Game stability         | Play level for extended time   | Game runs without crashing               | Stable                         |
| T6      | Movement consistency   | Repeated movement inputs       | No lag or delay                          | Works correctly                |
| T7      | Jump height            | Jump across gap                | Player clears gap                        | Works correctly                |
| T8      | Gravity behaviour      | Fall from platform             | Player falls naturally                   | Works correctly                |

### Bugs
Here are some bugs that were fixed

| Bug ID | Issue                         | Cause                          | Fix Applied                        | Retest |
| -----: | ----------------------------- | ------------------------------ | ---------------------------------- | ------ |
| B1     | Jump felt too slow            | Low jump force                 | Increased jump strength            | Pass   |
| B2     | Player clipping platform edge | Collision not properly aligned | Adjusted collision settings        | Pass   |
| B3     | Movement too fast             | Speed value too high           | Reduced movement speed             | Pass   |

### Conclusion 
Testing confirmed that core gameplay mechanics such as movement, jumping, and platform collision are functioning correctly. Minor issues were identified and resolved, improving overall gameplay stability. Further testing will be required as additional features are implemented.

# 13. References


# 14. Evaluation

The project has successfully progressed through the initial development stages, with core gameplay features such as movement, jumping, and level design implemented.

One of the strengths of the project is the clear structure and planning using Agile methodology, which helped organise development into manageable stages. The use of modular design also supports future expansion.

However, development is still ongoing, and some planned features such as enemies, UI systems, and level progression have not yet been fully implemented. Time management was a challenge when balancing development and documentation.

In the future, the project will be improved by adding more gameplay features, refining mechanics, and completing full testing. Overall, the project demonstrates a solid understanding of software development processes and game design principles.


