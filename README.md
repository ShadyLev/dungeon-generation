Instruction on how to set up the generation:
1) Create an empty game object and add the Room Templates script on it
2) Add rooms into the arrays ( each room is called by the doors it has so room called BR (bottom - right) will go into the bottom rooms array ect.
3) Add the boss prefab you want to spawn in the last room and select a wait time ( around 5-7 seconds depending on how big you want the dungeon to be)
4) Type in the max amount of rooms you want
5) Add the NavMeshSurface script reference
6) From prefabs add the entry room onto the main scene
7) Run the project!

If you want the NavMesh to generate add the NavMesh Components to the project from here: https://github.com/Unity-Technologies/NavMeshComponents
