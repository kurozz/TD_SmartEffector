# Tree Diagram Smart Effector design files repository.

![Top 3D View](/SmartEffector/td_smarteffector_v1.0/td_smarteffector_top3d.png)
![Bottom 3D View](/SmartEffector/td_smarteffector_v1.0/td_smarteffector_bot3d.png)

Based on the Duet3D Smart Effector, see www.duet3d.com for the original Duet3D Smart Effector information. This reproduction/modification is not endorsed or supported in any way by Duet3D

This design is meant for 24V, 12V is possible but requires dessoldering LEDs and adding jumpers.

## Changes from the original Smart Effector v3.0:
- Connectors heavily modified
    - All cables from the Duet controller board on a single connector
    - All cables from the effector on the same side of the board
- 6 illumination LEDs instead of 3.
- LEDs are 24V only. You can use 12V by soldering jumpers in place of 3 LEDs.
- Different regulator and amplifier to be easier to source.
- Works with the same firmware as Smart Effector v3.0.

Tree Diagram Smart Effector

Design by Kuro.

Original Design by Tony Lock and David Crocker

LICENSE: see the LICENSE file in the repository

Documentation: https://docs.duet3d.com/Duet3D_hardware/Accessories/Smart_Effector


Developed in KiCAD v6: https://www.kicad.org/
