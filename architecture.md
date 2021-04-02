
## Project Overview

The purpose of our project is to create a 3rd person platformer that engages the player through each floor with different enemies, hazards, and objectives.
The project will contain a ability system that will house 7-9 different abilities. The UI for this system will be located directly in the bottom center of the screen and will support a drag and drop functionality. 
The project will consist of 2-3 different floors, each floor consisting of the level. This will be scaled vertically so the player will progress through our game by navigating up the tower. 


## Key Architectural Drivers

Flexibility - All the data and code that is created in our project exists in one engine. This allows us to easily modify our code, assets, blueprints, or any other aspects without relying on external sources. (e.g. Blender, Zaz)


Performance- In this project we wanted to be able to keep track of all changing events and data as the game progresses. To maintain efficiency we chose a single engine to design our project so we can edit our code without the sacrifice of performance. 

## Architectural Style Choices

- Client-Server: This architecture is beneficial for our project because it allows the gamestate to constantly send and receive requests based on inputs. This also allows our data to be centralize in a single engine. This directly allows us to modify the code or assests at a low computational cost. This can also be very easy to manage all of our data and code as it is located on a singular source. Another advantage of this architecture is that it allows for the implementation of more local servers which can compliment each other during runtimes or performances.

- Publish-Subscribe



## Our Architecture (Client-Server/Publish-Subscribe)
![KeyArt](https://user-images.githubusercontent.com/77936719/113371716-432c1400-9324-11eb-8017-18154bc76ac4.JPG)
![ArchitectureDiagram](https://user-images.githubusercontent.com/77936719/113371721-458e6e00-9324-11eb-9625-02df99f9a765.JPG)



## Conclusion

Our architectural style is a combination of Client-Server and Publish-Subscribe. 
Possible Issues:
- Too complex/convoluted
- Constantly changing
- Difficult to gauge the aspects of data
- Constant maintenance is required to monitor status of the game 
