# SAC NPC

This was a passion project where I developed an NPC system to support an ArmA-inspired MILSIM group. Largely inspired by Hitman and Call of Duty: Cold War, this NPCs are able to roam, patrol, perform some tasks, react to surroundings (gunshots, visible weapons, trespassing, etc.), and is designed to allow stealth-like gameplay (blend, hide, walk) and combat gameplay (shoot, move, evade).

We implemented this to handle up to 100 NPCs in a 15-player server. Without implementing this using parallel LuaU, and much before the Roblox dynamic NPC behaviour, we saw an impressive client and server performance. Particularly, we saw a 5% failure rate for pathfinding, and a 100% success rate in NPC response.

We planned for dialogues, tasks, and environment-interactions for these NPCs as an extended goal. However, as we debanded in the spring of 2024, I ultimately scrapped this project and denoted as an important learning experience.

This project is now open for anyone who's willing to:
- Port it out of Knit/into an ECS
- Build upon it to achieve my previous visions, or
- Use it as a point of learning
