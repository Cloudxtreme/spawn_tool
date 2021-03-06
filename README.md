# spawn_tool (temp name)
Fork of Panda_Zonewalk, the goal is to develop an EQEmu World Editor (spawns, waypoints etc).

The rough idea as of now would be to have a tool capable of:

- opening a zone in a 3D-view
- fetching spawn data from an EQEmu database
- loading spawn data/points into the 3D view as basic shapes
- clicking on those objects would let us manipulate their position in real time and update the coordinates into the db
- waypoints would be governed by the same set of principles
- additionally, this kind of functionality could be extended into a fully-fledged world editor

As of right now, it is possible to load a fully-textured zone, explore it, and have it populated with spawn data from
the configured EQEmu DB.

The next steps is to implement basic GUI components and update spawn data.