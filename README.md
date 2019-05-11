# Crossy-Road-Unreal
My version of the game crossy road on mobile
Final Project, Crossy Road, due Friday, 19 May 2019 (by 2355)
In this assignment, you will recreate the classic Crossy Road game, using the Unreal 4 Engine, assets
created using a Voxel editor such as MagicaVoxel, and code written either in C++ (written to interface with
Blueprints and the Unreal framework), or with Blueprints, or both.
 The 3d assets you will need will all have to be created using an Voxel editor such as MagicaVoxel, or from
other 3d asset sources from Unreal. The audio resources you will need can be captured using an audio
editor such as Audacity from Crossy Road running on a laptop or desktop computer, or running as an iOS
or Google app on a mobile phone.

OBJECT OF THE GAME:
Live as long as possible. There is only one level, but it is dynamic and keeps being created in front of you, and
destroyed behind you.
The level is made up of alternating safe areas and obstacles with either vehicles that can strike you, or water you can
fall into. You can pause and wait for a safe interval to cross the obstacles -- but not too long, or an eagle will swoop
down and pick you off. Unlike the Lord of the Rings or the Hobbit, eagles are not good guys in this game.
Safe areas are grass w/ trees, bushes, and rocks). Obstacles are roads w/ vehicles, RR's w/ trains, or rivers w/ water
(unsafe) and moving logs (temporarily safe)).
You can move forwards/right/left always, and backwards only within a single safe area/obstacle. (However, most safe
areas are only one jump wide.)
The game designer must create the obstacles with moving cars/trucks, trains, or logs so that it is always possible for
the player to get through if they are clever enough. This means that cars/trucks/trains must be timed, and trees/bushes/
stumps/rocks must be placed properly.
The actor can be killed by either standing still or failing to move forward for too long (an eagle swoops down), or by
being run over, or by running into the side of a car/truck/train, or by falling into a river.
The special effects that occur are as follows:
• running into the side of a car or ruck: flattened version of voxel
• being run over by car or truck: flattened front of voxel on the highway
• being run over by/running into the side of an oil truck: explosion in three/four colors: bright, white, large, explosion
(polygon), then a particle system with the actor’s color, then yellow, then red (see images)
• being run over by/running into the side of a train: explosion of particles of the actor’s colors
• falling into water: exploding water particles
