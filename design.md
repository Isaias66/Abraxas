# Current Architecture
![KeyArt](https://user-images.githubusercontent.com/77936719/115084871-b443fd80-9ec6-11eb-9258-78d533ed6c22.JPG)
![ArchitectureDiagram](https://user-images.githubusercontent.com/77936719/115084813-a2625a80-9ec6-11eb-880e-89e041c014f1.JPG)

Our current architecture is a combination of Client-Server and Publish-Subscribe architectures. In regards to the Client-Server side of our architecture our same itself will be on the server side and will be downloaded and run on the clients side. This is the only interactioon between the client and our server since our game is not online. In a Publish-Subscribe architecture components of the project will react to events as they occur. In the case of our project our components will be the player and the game world, while events will be reactions such as combat and completing tasks that the player and the game world will react to. An example of this is the player will react to enemies attacking them by loosing health and vice versa. Another example is how the level will react by opening up more when certain tasks are completed on each floor.

# Class Diagram
