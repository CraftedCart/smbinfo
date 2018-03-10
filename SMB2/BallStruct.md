# SMB2 Ball Struct

Offsets for data contained within each of the 8 ball structs, relative to the start of the struct.

### Relative Offsets

- `0x0`: Is Active? (Byte)
- `0x1`: Unknown (Byte)
- `0x2`: Unknown (Byte)
- `0x3`: Something to do with physics state (Crashes the game if set wrong) (8 bit bitmask)
- `0x4`: X-Position (Float32)
- `0x8`: Y-Position (Float32)
- `0xC`: Z-Position (Float32)
- `0x10`: X-Position last frame (Float32)
- `0x14`: Y-Position last frame (Float32)
- `0x18`: Z-Position last frame (Float32)
- `0x1C`: X-Velocity (Float32)
- `0x20`: Y-Velocity (Float32)
- `0x24`: Z-Velocity (Float32)
- `0x28`: Unknown Angle/Rotation (Short16)
- `0x2a`: Unknown Angle/Rotation (Short16)
- `0x2c`: Unknown Angle/Rotation (Short16)
- `0x2e`: Padding (Short16)
- `0x30`: Unknown Angle/Rotation (Float32)
- `0x34`: Unknown Angle/Rotation (Float32)
- `0x38`: X-Axis Angle (Float32)
- `0x3C`: X-Position Copy (Float32)
- `0x40`: Unknown Angle/Rotation (Float32)
- `0x44`: Unknown Angle/Rotation (Float32)
- `0x48`: Y-Axis Angle (Float32)
- `0x4C`: Y-Position Copy (Float32)
- `0x50`: Unknown Angle/Rotation
- `0x54`: Unknown Angle/Rotation
- `0x58`: Z-Axis Angle (Float32)
- `0x5C`: Z-Position Copy (Float32)
- `0x60`: Unknown Angle/Rotation (Short16)
- `0x62`: Unknown Angle/Rotation (Short16)
- `0x64`: Unknown Angle/Rotation (Short16)
- `0x66`: Padding (Short16)
- `0x68`: Ball Physical Size (Float32)
- `0x6C`: Acceleration (Float32)
- `0x70`: Restitution (Float32)
- `0x74`: Ball Visual Scale (Float32)
- `0x78`: Number of Bananas (Int32)
- `0x7C`: Score (Int32)
- `0x80`: Level Stopwatch (Int32)
- `0x84`: Unknown
- `0x88`: Unknown
- `0x8C`: Unknown
- `0x90`: Unknown
- `0x94`: Unknown
