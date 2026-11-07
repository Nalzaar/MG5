# MG5
## Devlog
1. I think it's more advantageous to use a NavMesh vs scripting a character's movement with physics when you don't have as much dynamic interaction between a character on the environment. When scripting physics, you have more things to consider so if you don't have as much interaction, it's better to instead use NavMesh. For example, if your game mainly consists of just jumping and navigating a map to reach a checkpoint then it's not as interaction heavy and would be better to just stick to NavMesh. On the other hand let's say that there is a similar game, but it also has features such as traps in where the player is sent flying away based on how they landed or were hit by a trap. You would need to create a script to make the interactions vary based on all these extra forms of interaction.
2. The for loop is comparing the distance between the player's position and that of each bird. The Vector3 gets the position of all 4 objects and then the operator checks if the player is at or is closer than a set distance that is represented by the _interactDistance variable.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)