## WorldSync

Requirements:
6 Bools
1 Float
3 Contact Senders
12 Contact Receivers
2 Phys bones
1 Phys bone collider


This Prefab keeps your world drops synced from your avatar with no external programs. 

### Install instructions.

1. Place the Prefab/World Constraint on your avatar. 

![Prefab Placed On Avatar](https://i.imgur.com/FvvMXA3.png)

2. Unpack the World Constraint prefab completely.

![Unpack Prefab](https://i.imgur.com/VnJSYVC.png)

3. Place the ResetTarget on some part of your Armature. I like using my Right Wrist. You can place it anywhere. Make sure it matches up on the position on the avatar. You may need to 0 out the position and rotation.

![Place ResetTarget](https://i.imgur.com/aV0Qb3N.png)

4. Open the World Constraint/RotationSource and drag your Armature into the "Rotation Constraint" Sources.

![Place Armature in RotationConstraint](https://i.imgur.com/5jWgcn8.png)

5. Place the Animator/WorldSync on your FX layer.

![Place FXLayer](https://i.imgur.com/G8WWrsz.png)

6. Place the WorldSync Params and Menu on your avatar.

![WorldSync Params and Menu](https://i.imgur.com/TjeQEx2.png)

7. Place your Target object (for example a couch) in the World Constraint/Container/Toggle with it ON and adjusted however you want. Once you are happy with its relative positioning, turn the toggle object back off. In the image below, I adjusted my object to be further in front of me by moving the Z position. You can also just leave the position at 0,0,0. There is a SAMPLE CUBE you will want to remove in that same spot.

![TargetObject](https://i.imgur.com/6DnB2Pv.png)

Upload.

When you drop the object. It should drop instantly, then after a few seconds it will swap to the remote version which should stay synced for everyone involved. It may disappear for a frame, it shouldn't but it may.

This supports worlds of size +-1000,+-1000,+-1000.

The layers in the animator for this are prefixed with WorldSync. If you want to use a custom WorldDrop animation you can disable the WorldSync_WorldDrop layer. This layer plays a very simple toggle that sets "Toggle" to enabled and disabled based on the WorldDrop Parameter. Do NOT modify any other layers.

If you would like to copy the animator to your primary animator make sure to make a Copy and use the VRLab Av3 Manager linked below. If you do this, make sure that you don't already have the same parameters in your project.

https://github.com/VRLabs/Avatars-3.0-Manager

Compiled by Juzo and Razgriz

Shoutouts to the VRLabs team especially Lin. Thank you for your help on this project.
