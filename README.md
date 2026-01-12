[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## Devlog
Allen, he/him

My MG1 break-down plan focused on moving the player and planting seeds while updating the UI. In my Unity scene, the Player GameObject uses the Player script, where movement is handled in Update() using the keyboard, and planting a seed happens when the player presses Space, which calls PlantSeed(). In PlantSeed(), a plant is created at the player’s position using Instantiate(), and the seed counts are updated. To make sure the UI always shows the correct numbers, the Canvas GameObject uses the PlantCountUI script, which receives the updated values from the Player script through UpdateSeeds().


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
