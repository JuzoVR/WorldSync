# WorldSync


## [Click here for Latest Release](https://github.com/JuzoVR/WorldSync/releases)

Requirements:

  6 Bools
  
  1 Float
  
  3 Contact Senders
  
  12 Contact Receivers
  
  2 Phys bones
  
  1 Phys bone collider


This Prefab keeps your world drops synced from your avatar with no external programs. 

# MANDATORY PREREQUISITE

Follow Installation instructions for Modular Avatar

https://modular-avatar.nadena.dev/docs/intro

# This is mandatory.

### Install instructions.

1. Place the Prefab/World Constraint on your avatar. 

![Prefab Placed On Avatar](https://i.imgur.com/hM8Fvx7.png)

2. Unpack the World Constraint prefab completely.

![Unpack Prefab](https://i.imgur.com/LSxOZGC.png)

3. Open the prefab and select the ResetTarget. You can drag this onto your ARMATURE Hips is the minimum depth. If youd like to have your position and rotation separate. (for example position on hands and rotation on hips.) You can open the ResetTarget and select the individual PositionTarget and RotationTarget and place them in their relative positions.

![Place ResetTarget](https://i.imgur.com/sSRrVFW.png)

4. Replace the Cube under World Constraint/Container/Toggle with your own object. Make sure to 0 it out or set whatever offset you would like. 

![Replace Cube with your Target Object](https://i.imgur.com/mmHBUm2.png)

You're done.

Upload.

When you drop the object. It should drop instantly, then after a few seconds it will swap to the remote version which should stay synced for everyone involved. It may disappear for a frame, it shouldn't but it may.

This supports worlds of size +-1000,+-1000,+-1000.

Example Video for set up:

https://github.com/JuzoVR/WorldSync/assets/99932870/eaabddcd-a7c8-4420-bae6-7709f2d1f212

Example video for placing on Avatar Pill (so it drops at the floor at the same height every time)


https://github.com/JuzoVR/WorldSync/assets/99932870/4e015c95-ff76-48a7-a6d2-da5537244ec8



Example video for placing on hand


https://github.com/JuzoVR/WorldSync/assets/99932870/55f705f7-3bde-4b88-a4eb-d6caeff09a2b


Example video for putting rotation on hip while keeping position on hand



https://github.com/JuzoVR/WorldSync/assets/99932870/24a3b78e-4bcf-405d-8445-8c5b6792e1fc



Update:

Added forceLocal variable. If you wish to override the sync with a local drop (if it breaks in an sdk2 world for example) you can toggle it on.

Compiled by Juzo 

Shoutouts to the Razgriz for their help on theory and the VRLabs team especially Lin. Thank you for your help on this project.

Version 3.04.2024.0
