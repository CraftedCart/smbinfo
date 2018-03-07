Memory Addresses
================

- `805BC470`: DIP switches (32 bit bitmask)
- `805BCA1C`: Score (Int32)
- `80553974`: Timer (Signed Short16)
- `805BC9BC`: X-Velocity (Float32)
- `805BC9C0`: Y-Velocity (Float32)
- `805BC9C4`: Z-Velocity (Float32)
- `80446C20`: Monkey Visibility (Byte?)
- `80145120`: Button Input (32 bit bitmask)
- `805BC9A4`: X-Position (Float32)
- `805BC9A8`: Y-Position (Float32)
- `805BC9AC`: Z-Position (Float32)
- `8055399C`: Next Level (Computed on goal) (Short16)
- `80553991`: Current Level (First byte) (Byte)
- `8054E058`: Camera camx (Float32)
- `8054E05C`: Camera camy (Float32)
- `8054E060`: Camera camz (Float32)
- `8054E064`: Camera intx (Float32)
- `8054E068`: Camera inty (Float32)
- `8054E06C`: Camera intz (Float32)
- `8054E070`: Camera angx (Short16)
- `8054E072`: Camera angy (Short16)
- `8054E074`: Camera angz (Short16)
- `804724BC`: Ball acceleration per frame (Float32)
- `804724C0`: Ball bounce restitution (How much energy is lost in a collision | Float32)
- `804724B8`: Physical ball size (Float32)

## Timer Pre Restart

- `805E94C8`: Ball red (Byte8)
- `805E94C9`: Ball green (Byte8)
- `805E94CA`: Ball blue (Byte8)
- `805E9508`: Ball speed (Int32)
- `805E950C`: Flash speed (Int32)
- `805E9510`: Flash pos? (Int32)
- `805E9538`: Ball angle (Short16)

## After Restart

- `805E93F8`: Ball red (Byte8)
- `805E93F9`: Ball green (Byte8)
- `805E93FA`: Ball blue (Byte8)
- `805E9438`: Ball speed (Int32)
- `805E943C`: Flash speed (Int32)
- `805E9440`: Flash pos? (Int32)
- `805E9468`: Ball angle (Short16)

