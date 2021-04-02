
## Our Architecture (Client-Server/Publish-Subscribe)
![KeyArt](https://user-images.githubusercontent.com/77936719/113371716-432c1400-9324-11eb-8017-18154bc76ac4.JPG)
![ArchitectureDiagram](https://user-images.githubusercontent.com/77936719/113371721-458e6e00-9324-11eb-9625-02df99f9a765.JPG)

In this diagram it displays the various relationships that each part in our architecture. The player controller first begins by joining the gamestate and gamemode. This is considered the source server and is where all data, input, subscribers, and other forms of code is sent back and forth to be processed. Note that the player controller and AI controller "possess" the pawn object. This allows objects such as pawn actors to be controlled (possessed) by different controllers in order to represent physical objects within the game. 



