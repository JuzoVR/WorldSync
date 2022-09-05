### WorldSync

Requirements:
6 Bools
1 Float
3 Contact Senders
12 Contact Receivers
2 Phys bones
1 Phys bone collider
This Prefab keeps your world drops synced from your avatar with no external programs. 

Install instructions.

1. Place the Prefab/World Constraint on your avatar. 

2. Unpack the World Constraint prefab completely.

3. Place the WorldDropTarget on some part of your Armature. I like using my Right Wrist. You can place it anywhere. Make sure it matches up on the position on the avatar. You may need to 0 out the position and rotation.

4. Open the World Constraint/RotationSource and drag your Armature into the Parent Constraint Sources.

5. Place the Animator/WorldSync on your FX layer.

6. Place the WorldSync Params and Menu on your avatar.

7. Place your Target object (for example a couch) in the World Constraint/Container/Toggle with it ON and adjusted however you want. Once you are happy with its relative positioning, turn the toggle object back off.

Upload.

When you drop the object. It should drop instantly, then after a few seconds it will swap to the remote version which should stay synced for everyone involved. You will likely notice that it rotates a little bit when its synced.

This supports worlds of size +-1000,+-1000,+-1000.

If you would like to copy the animator to your primary animator make sure to make a Copy and use the VRLab Av3 Manager linked below.

https://github.com/VRLabs/Avatars-3.0-Manager

Compiled by Juzo and Razgriz

Shoutouts to the VRLabs team especially Lin. Thank you for your help on this project.
