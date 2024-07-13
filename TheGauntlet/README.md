# The Gauntlet
Link to play https://dariusfang.itch.io/the-gauntlet

## Challenges Faced During Assignment:
The hardest part of the assignment was making sure the game ran smoothly from start to finish as well as the gameplay flow. After the first release, a lot of time was spent optimizing the game using techniques like LOD, occlusion culling, and static batching to improve performance.

### Updated Features:

    Performance Improvements: Reduced the rendering of meshes when the player is far away to improve performance.
    Code Refactoring: Cleaned up and improved the code following SOLID principles.
    New Gameplay Elements: Added lava, parkour sections, and moving platforms to make the game more exciting.

## Features:
- Puzzles
- Use of Game architectures, classes, design patterns

## Notable Scripts
- InputController: contains a list of modules to be used for player input
- GameManager: invokes events when a player has died, puzzles have started, and all puzzles have finished.
- InteractModule: Allows for the player to ray cast onto an interactable object to be used to invoke interactions.

  ![PickupBlock ](https://github.com/DarFang/Itch.io-Builds/assets/56571687/3c8c617c-941b-413f-b986-cb83ba5c550c)

- DisplayButton: Generic display button to be used with my puzzle Scripts.
  
  ![Display](https://github.com/DarFang/Itch.io-Builds/assets/56571687/88ab2d6f-932c-495c-ab41-0b54c808807c)
  
- Button: Generic button to be used to invoke an event.
  
  ![Buttton ](https://github.com/DarFang/Itch.io-Builds/assets/56571687/1f893ba4-8550-4ac7-915e-db6fc0c06a22)

- Simon Says: Sequence of numbers to be compared to the player input. It generates, plays a sequence, and determines if the player wins or loses.
  
  ![SimonSays](https://github.com/DarFang/Itch.io-Builds/assets/56571687/448b9a7f-5070-46b3-8bf1-f5eb0612b67d)
  
- LightsOut: Similar to Simon Says, it generates, and determines if the player wins.
  
  ![Lightsout ](https://github.com/DarFang/Itch.io-Builds/assets/56571687/045e99c0-1408-45de-b165-1d875165a04c)

- Wires: Controls a list of wires to be connected using nodes, and line renderer.
  
  ![Wires ](https://github.com/DarFang/Itch.io-Builds/assets/56571687/6369c196-ae7c-45d7-b6d8-51232cc4cd72)


- AITurretState: Controls the state of the turret to either damage or idle.
  
  ![TurretLaser ](https://github.com/DarFang/Itch.io-Builds/assets/56571687/9f6eb007-c812-4cda-8c3f-be3192008fc2)


## Demo:
https://github.com/DarFang/Itch.io-Builds/assets/56571687/83819b57-4c9e-476e-aec5-d898f0146005

### Explore my other games: https://github.com/DarFang/Itch.io-Builds

