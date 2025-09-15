# MrK's MultiPlayerThirdPersonPlayerArena
Networked Arena Combat

Run with UE5.6 using .uproject

1. Used standard combat template from UE5.6
2. Remade animation calls, widgets and stats to work in networked environment
3. Added animation budget allocation, Epic's suggested alternative to update rate optimization
4. Added custom config in DefaultGame.ini with network usage optimization
5. Modified standard map to include collectibles
6. 3 Types of collectibles:
	1. Health Packs
	2. Weapons (simple visual attachment, doubles the damage)
	3. Match Start (special collectible)
7. Made Custom widgets for hud and collectibles using CommonUI for the most part
8. Summary screen shown on match end (after reaching goal), only host can return all players to lobby
9. Lobby map with a Match Start collectible (only host can use it)

Tested Combat mechanics with 2 players under one process
Tested Server Travel using Multiple processes
Further testing should be conducted using multiple PCs or dedicated server
