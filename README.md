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
9. [Game Design](#9-game-design)
10. [Technology Used](#10-technology-used)
11. [Development Strategy](#11-development-strategy)
12. [Scrum Backlog](#12-scrum-backlog)
13. [Project Management](#13-project-management)
14. [Testing](#14-testing)
15. [Challenges & Solutions](#15-challenges--solutions)
16. [Evaluation](#16-evaluation)
   
## 1. Project Overview
Penguin Ice Quest is a 2D side-scrolling platform game in which the player controls a penguin navigating through icy environments. The aim of the game is to collect fish, avoid enemies, and minimise damage while progressing to the end of each level.

The player begins with three lives and must collect a required number of fish to unlock new levels. As the game progresses, levels increase in difficulty, introducing new challenges and obstacles.

The game concept was inspired by the mobile platform game Lep’s World. While inspired by Lep’s World, Penguin Ice Quest features original characters, environments, and gameplay mechanics.

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

## 9. Game Design
Player

The player controls the main character using keyboard input. The character can move left and right across the level and perform jumps to navigate obstacles and platforms. The movement system was designed to be responsive and easy to use, ensuring that players can accurately control the character throughout gameplay.

Environment

The game takes place in a 2D platforming environment consisting of multiple platforms positioned at varying heights. The player must navigate these platforms while avoiding hazards and collecting items. The environment is designed to gradually increase the challenge by requiring more accurate jumps and movement.

Gameplay Loop

The core gameplay loop follows a simple platform game structure:

Explore Level → Move Between Platforms → Collect Items → Avoid Hazards → Reach Level Exit → Progress

This loop provides the player with clear objectives while encouraging exploration and skill development throughout the game.

Game Rules
The player can move left and right using keyboard controls.
The player can jump to reach higher platforms.
Falling off the level results in failure and a restart.
Collectibles can be gathered to increase progression.
The objective is to reach the end of the level successfully.
## 10. Technology Used
Game Engine

Godot Engine

Programming Language

GDScript

Development Tools
Godot Editor
Visual Studio Code
GitHub
Git Version Control

Godot was selected because it provides a lightweight development environment with strong support for 2D game development. The engine includes built-in physics, collision detection and scene management systems, allowing core gameplay mechanics to be implemented efficiently.

GitHub was used for version control throughout development, enabling project progress to be tracked and changes to be managed effectively.
## 11. Development Strategy
The project follows an iterative development strategy based on Agile principles. This approach was chosen because it allows the game to be developed in small, manageable stages while continuously reviewing progress.Instead of attempting to build the entire game at once, the development was broken down into smaller features such as movement, jumping and collision detection. Each feature would be planned, implemented and then tested before moving on to the next stage. This reduces the risk of major errors and makes debugging easier.A Scrum-style workflow was used to organise tasks. Features were added to a backlog and prioritised based on importance. Core mechanics such as player movement and jumping were given the highest priority, while additional features like coins and enemies were considered lower priority and planned for later stages.This structured approach ensured that the most important parts of the game were focused on first. It also allowed flexibility, meaning changes could be made if issues were identified during development.Version control using GitHub was used to manage the project. This allowed progress to be tracked over time and ensured that different versions of the work could be saved and reviewed.

### Burndownm chart 
The burndown chart demonstrates the gradual completion of project tasks throughout development. Core gameplay mechanics such as movement, jumping and collision detection were prioritised first, followed by level design, collectibles, enemy implementation, testing and documentation. The chart shows a steady reduction in remaining work, reflecting the iterative Agile-inspired development process used throughout the project.

| Week | Tasks Remaining |
|------|----------------|
| 1 | 15 |
| 2 | 13 |
| 3 | 10 |
| 4 | 7 |
| 5 | 4 |
| 6 | 0 |


### State Diagram
                 ┌───────────┐
                 │ Main Menu │
                 └─────┬─────┘
                       │
                       ▼
                ┌────────────┐
                │  Playing   │
                └───┬────┬───┘
                    │    │
          Fall/Hit  │    │ Reach Exit
          Enemy     │    │
                    ▼    ▼
             ┌────────┐ ┌──────────────┐
             │ Game   │ │ Level        │
             │ Over   │ │ Complete     │
             └────┬───┘ └──────┬───────┘
                  │            │
                  ▼            ▼
             Restart      Next Level
                  │            │
                  └─────┬──────┘
                        ▼
                    Playing

The game begins at the Main Menu. Once the player starts the game, they enter the Playing state where movement, jumping, collectibles and enemy interactions occur. If the player falls off the level or collides with a hazard, the Game Over state is triggered and the level restarts. Successfully reaching the level exit transitions the player to the Level Complete state, allowing progression to the next level.

## 12. Scrum Backlog
Feature	Priority	Description	Test Criteria
Player Movement	High	Allow the player to move left and right using keyboard input	Player moves smoothly left/right when keys are pressed
Jump Mechanic	High	Implement jumping using gravity and physics	Player jumps and lands naturally without floating
Platform Collision	High	Ensure player can stand on platforms without falling through	Player lands on platforms and does not pass through them
Camera Follow	Medium	Camera follows the player as they move through the level	Camera tracks player smoothly without lag
Level Design	Medium	Create platforms at different heights for navigation	Player can move across the level using jumps
Game Restart	High	Allow the game to restart after player falls or loses	Game resets correctly when player loses
Testing & Debugging	High	Identify and fix bugs in movement and collisions	No major bugs during gameplay

Scrum Backlog
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

## 13. Project Management
### Week 1 - Project Setup & Planning
#### Date: W/C 16 February 2026
#### Completed:
- Created GitHub repository
- Structured README file
- Sections 1-8 of README completed
- Planned initial Scrum backlog
- Set up Godot project structure
- Configured initial scenes and player character
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


### Week 5
Added enemies and coins.

### Week 6
Testing and bug fixing.

Development Meetings
Development Meetings
###  Development Review Meeting 1
Discussed overall game idea and core features. Decided to focus on a simple platformer with movement and jumping.

###  Development Review Meeting 2
Reviewed progress and identified challenges with implementing physics and collision detection. Planned next steps for improving gameplay.

###  Development Review Meeting 3
Evaluated overall project progress and focused on documentation, testing and final improvements.

### Development Review Meeting 4

Completed Since Last Meeting:
- Implemented collectible items
- Added enemy hazards
- Improved level layout

Planned Tasks:
- Perform testing
- Fix gameplay bugs
- Update documentation

Current Problems:
- Collision issues with some objects
- Balancing jump distances

- ### Development Review Meeting 5

Completed Since Last Meeting:
- Completed testing
- Fixed collision bugs
- Updated README documentation

Planned Tasks:
- Final review of project
- Prepare GitHub submission
- Record project demo

Current Problems:
- Limited time available for additional features

## 14. Testing
| Test               | Expected Result                | Actual Result                | Status |
| ------------------ | ------------------------------ | ---------------------------- | ------ |
| Move Left          | Player moves left              | Player moved left correctly  | Pass   |
| Move Right         | Player moves right             | Player moved right correctly | Pass   |
| Jump               | Player jumps and lands         | Jump worked correctly        | Pass   |
| Platform Collision | Player lands on platform       | No clipping detected         | Pass   |
| Collect Item       | Item disappears when collected | Item collected successfully  | Pass   |
| Reach Exit         | Next level loads               | Level completed correctly    | Pass   |
| Fall Off Map       | Level restarts                 | Restart triggered correctly  | Pass   |

## 15. Challenges & Solutions
One challenge was implementing collision detection between the player and platforms. This caused issues where the player would fall through objects. Another challenge was balancing development time while refining the jump mechanics. Several adjustments to gravity and jump strength were required before the controls felt responsive and natural.
### Gameplay Screenshot 1 Main Menu
### Gameplay Screenshot 2 Gameplay
### Gameplay Screenshot 3 Collectible Fish
### Gameplay Screenshot 4 Enemy Hazard
### Gameplay Screenshot 5 Level Complete
### Gameplay Screenshot 6 Game Over
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b7921db6-2030-4b30-b78a-a748ea9616ee" />

## 16. Evaluation
The project successfully demonstrates the development of a functional 2D platform game. Core gameplay features including player movement, jumping, collision detection and level navigation were implemented successfully. The project also demonstrates the use of software development principles such as planning, testing, debugging and iterative development.

One of the project's main strengths is the implementation of responsive player controls, which provide a solid gameplay experience. The use of a structured development process also helped organise tasks and monitor progress throughout the project lifecycle.

However, the project has several limitations. Due to time constraints, some planned features were simplified or not fully implemented. Additional levels, improved artwork, sound effects and more advanced enemy behaviours would further enhance the player experience.

Future development could include additional levels, improved visual assets, enhanced user interface elements, a scoring system, save functionality and more complex gameplay mechanics. These improvements would increase both the depth and replayability of the game.

Overall, the project achieved its primary objectives and provided valuable experience in software design, implementation, testing and project management.

