
# Requirements Specification for Abraxas
## 1. Introduction
1.1 Purpose of Product

The purpose of our project is to create a third-person RPG style platformer. This game will comprise of a unique ability system that houses 6-8 different abilities. Scattered throughout each level will be enemies, hazards, and a unique task that the player must finish before progressing into the next level. This will provide entertainment and creative approaches for the player to navigate during each level. This game will take place in a tall tower in which the player must climb in order to ascend to the next level. 

1.2 Scope of Product

Our game will contain 3 levels that house two floors. Each level will contain a new mechanic such as a bounce pad, hazardous pit, and moving platforms. This will not contain a skill tree progression system and instead provides the player with the customization of all their powers from the beginning. These powers will utilize a power bar that gradually regenerates over time. 

1.3 Acronyms, Abbreviations, Definitions

- BB: Black Board (A supplimentary system to BT, assists in more specilized and customized actions for AI)
- BT: Behavior Tree (A integrated system within Unreal Engine that programs descisions by AI)

1.4 References

- AI Documentation: https://docs.unrealengine.com/en-US/InteractiveExperiences/ArtificialIntelligence/index.html
- Behavior Tree Documentation: https://docs.unrealengine.com/en-US/InteractiveExperiences/ArtificialIntelligence/BehaviorTrees/index.html 
- Blackboard Documentation: https://docs.unrealengine.com/en-US/BlueprintAPI/AI/Components/Blackboard/index.html

## 2. General Description of Product

2.1 Context of Product

Our product will be created and held in the Unreal Engine.  This is one of the more versatile and robust game engines for utilizing C++ and blueprints. This will forward our progression in our project by providing us with useful tools such as animation editors. Rather than utilizing separate third-party software, we will attempt to create all of our assets and code within on singular game engine. This will also allow for faster compiliations of our code and all us to manage all of our assests and code in one singular location. 

2.2 Domain Model with Description

![Abraxas Domain Model](https://user-images.githubusercontent.com/78187057/112574374-bc22ed00-8db3-11eb-80da-ccb9b735d87c.jpg)

Each basic aspect of the game is placed into the model to show it's relation to other elements. This is accomplished using arrows and 1 to 2 descriptive words. The head of the arrow shows which element or elements the former element relates to, while simultaneously existing to hopefully guide the eye in the direction that it is supposed to be.

2.3 Product Functions (general)

Our product will contain a variety of RPG and platforming aspects that intersect with each other to create a challenging experience. Within this game there will be a basic inventory system where the player can drag and drop different abilities onto their hot bar. This hot bar will be located directed underneath the power gauge and will be able to hold up to 8 different abilities at a time. This will grant the player more freedom and customization as they progress through the levels.

There will be a total of 7-8 abilities within this game. Each ability has certain aspects such as projectiles, DeBuffs, AoE, and Buffs to assist the player through the level. Many of these abilities will intertwine with the unique mechanic for each level. The UI for these abilities will be displayed in the bottom center of the player screen and are completely interactable by simply clicking on the ability's icon. Above the ability UI, there will also be a health and a power bar. These gauges will provide the player with a sense of strategy and planning on how they wish to use their powers


2.4 User Characteristics and Expectations

The primary demographic of our users will comprise of casual to daily gamers who have a good sense of how video games work. These players can range from a variety of genres such as FPS, RPG, Adventure, or puzzle games. Although our primary group will be players who have experience with video games, our game is still very accessible and easy to learn for any newcomers to the video game realm. Most of our players will have some experience with game logic such as platforming, shooting, or running so there will not be a steep learning curve within our game. We expect our players to have basic knowledge of defeating enemies, navigating on basic platforms, and recognizing any tasks that may be presented before them.

2.5 Constraints

There are multiple advantages and disadvantages to the game engine our project is utilizing. Unreal Engine utilizes C++ which can create difficulty with readability. This also correlates to the blueprint system which also utilizes C++, but the readability can decrease rapidly depending on the complexity of the code. There are no issues with computational power for graphics or real-world light simulations. 

2.6 Assumptions and Dependencies

Unreal Engine utilizes a graphics and image software database called Quixel. This was an external software that provided a multitude of different assets to incorporate into a project. Quixel was purchased by Unreal and is not implemented within the software for Unreal Engine. It is assumed that any PC running our project will be able to handle these assets at 30 FPS. However, since Quixel is automatically incorporated into Unreal Engine our project will not have any dependency issues when creating our project. 

## 3. Functional Requirements

[Link to our User Stories Page](https://isaias66.github.io/Abraxas/userstories)

## 4. System and Non-functional Requirements

Our game will essentailly have three main interfaces

- NF.4.1.1 :User interface in game with health, mana, and spells.
- NF.4.1.2 :A main menu to start the game and customize options.
- NF.4.1.3 :Loading screen

4.2 Performance Requirements

The hardware will require at a low to semi moderate PC to perform at an operable state. 

- NF.4.2.1 OS: Windows 7/8/10 64-bit or Mac OSX Sierra
- NF.4.2.2 CPU: Quad-core Intel or AMD processor, 2.5 GHz or faster.
- NF.4.2.3 RAM: 8 GB, recommended to have at least 32 GB.
- NF.4.2.4 GPU: NVIDIA GeForce 470 GTX or AMD Radeon 6870 HD series card or higher.
- NF.4.2.5 Video Card/DirectX Version: DirectX 11 or DirectX 12 compatible graphics card.

4.3 Design Constraints

Our design choices will have factors that include the users PC and some time constraints.
 
- NF.4.3.1 :Users PC hardware.
- NF.4.3.2 :Users monitor capabilities
- NF.4.3.3 :Scene Boundaries
- NF.4.3.4 :Getting correct physics for bounce bounce pad and other moving parts.
- NF.4.3.5 :Mouse and Keyboard Inputs
- NF.4.3.6 :Art Style

4.4 Quality Requirements

- NF.4.4.1 :Textures that the player can recognize (ie. Stone, Sand, Wood, Fire...)
- NF.4.4.2 :Art Style
- NF.4.4.3 :Theme 
- NF.4.4.4 :Non-essential Scenary
- NF.4.4.5 :Recognizable Scenary
 
4.5 Other Requirements

- NF.4.5.1 :None at this time

## 5. Appendices

Constraints Documentation:

- [Quixel](https://www.unrealengine.com/en-US/blog/unreal-engine-4-24-to-ship-with-free-quixel-megascans-unreal-studio-features-and-more)
- [Minimum Requirements](https://docs.unrealengine.com/en-US/Basics/RecommendedSpecifications/index.html)

