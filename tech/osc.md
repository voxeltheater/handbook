# OSC Dictionary

The Voxel itself has a growing API for OSC, allowing you to control it from any device or software which can send OSC messages. What follows here is a complete dictionary of The Voxel’s OSC implementation.

This API is designed to integrate aspects of the building, such as HVAC and work lights, into your show's cue list. For example, you can turn down the lobby lights automatically when you run a top-of-show cue.

*The Voxel OSC API must be used over UDP transport layer. The Voxel listens for incoming OSC at `voxel.local:5333`*

## Lighting

### /voxel/lobby/wallColor {string}
Select the primary color of the lobby lighting. Available options are "red", "orange", "green", "blue", and "purple".

### /voxel/lobby/globes {number}
Set the intensity of the hanging globe lights in the lobby. Range is 0-100.

### /voxel/lobby/specials {number}
Set the intensity of the specials focused on the tables on he lobby. Range is 0-100.

### /voxel/lobby/restrooms {number}
Set the intensity of the specials focused on the restroom signage in the lobby. Range is 0-100.

### /voxel/ramp/globes {number}
Set the intensity of the hanging globe light at the bottom of the ramp. Range is 0-100.

## Sound

### /voxel/lobby/volume
Set the gain of the lobby speakers. Range is -120-10. 

### /voxel/pcdi/enable
Un-mutes the PCDI input into the sound system.

### /voxel/pcdi/volume
Set the gain of the PCDI input into the sound system. Range is -120-24. 

