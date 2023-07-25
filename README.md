# Hero Squad Game Using Java Program

## Author: 
Josephine Kemuma

## Description: 
Week two Java Spark IP about the Hero Squad Game

## What is a squad game? 
A hero squad game is a tactical shooter based around a squad gameplay designed to encourage teamwork and communication. 

In a Hero Squad game, players typically have the following objectives and gameplay elements:

## Recruit Heroes: 
Players have the ability to select and recruit different heroes into their squad. Each hero possesses their own special powers, skills, and weaknesses. The players must strategically choose heroes with complementary abilities to form a strong and balanced team.

## Squad Formation: 
Players need to strategically assign heroes to their squad, considering factors such as team synergy, tactical advantages, and mission requirements. The squad formation plays a crucial role in determining the overall effectiveness and success of the team.

## Missions and Challenges: 
The game presents various missions, quests, or challenges that the Hero Squad must undertake. These missions can range from rescuing hostages, defeating supervillains, solving puzzles, or protecting the city from imminent threats. Players must navigate through different levels, face adversaries, and utilize their heroes' unique abilities to overcome obstacles and achieve the mission objectives.

## Turn-Based Battles: 
Hero Squad games often incorporate turn-based combat mechanics. Players engage in battles with enemies or other opposing forces, taking turns to execute actions and abilities. The outcome of battles depends on factors such as hero abilities, strategy, and tactical decision-making.

## Progression and Upgrades: 
As players advance through the game, they can earn experience points, currency, or other rewards. These can be used to level up heroes, unlock new abilities, acquire equipment or upgrades, and enhance the overall power and effectiveness of the Hero Squad.

## Team Management and Strategy: 
Successful Hero Squad games require players to manage their team effectively, including optimizing hero selection, upgrading abilities, managing resources, and devising strategies to overcome different challenges. Players must consider the strengths and weaknesses of each hero and adapt their strategies accordingly.

## Cooperative or Competitive Gameplay: 
Some Hero Squad games may offer cooperative gameplay options, allowing players to team up with friends or other players to tackle missions together. Alternatively, the game may feature competitive elements, such as PvP battles or leaderboards, where players can compete against each other to demonstrate the strength of their Hero Squads.

## BDD (Behavior-Driven Development)

### Feature: Recruit Heroes

#### Scenario: 
Successfully recruit a hero into the squad
Given the player is logged in and on the recruit page
When the player selects a hero from the available options
Then the hero is added to the squad roster
And the player receives a success message confirming the hero recruitment

#### Scenario: 
Cannot recruit the same hero twice
Given the player is logged in and on the recruit page
And the hero is already in the squad roster
When the player tries to recruit the same hero again
Then the player receives an error message indicating that the hero is already recruited

#### Feature: Squad Formation

Scenario: Assign heroes to the squad
Given the player is logged in and on the squad formation page
When the player selects heroes from the available roster
And assigns them to the squad slots
Then the heroes are successfully assigned to the squad
And the player can see the updated squad formation

#### Scenario: 
Squad size restriction
Given the player is logged in and on the squad formation page
And the squad has reached the maximum size limit
When the player tries to assign another hero to the squad
Then the player receives an error message indicating that the squad is already full

### Feature: Missions and Challenges

#### Scenario: 
Complete a mission successfully
Given the player is on the mission page
And the squad is prepared for the mission
When the player initiates the mission
Then the player receives mission details and objectives
And the squad engages in battles and completes the objectives
And the player receives rewards upon successful completion

#### Scenario: 
Fail a mission
Given the player is on the mission page
And the squad is not adequately prepared for the mission
When the player initiates the mission
Then the player receives mission details and objectives
And the squad struggles in battles and fails to complete the objectives
And the player receives a failure message



###### Copyright (c) 2023 **Josephine Kemuma**