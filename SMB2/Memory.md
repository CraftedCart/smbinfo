Memory Addresses
================

- `805BC470`: DIP switches (32 bit bitmask)
- `80553974`: Timer (Signed Short16)
- `80446C20`: Monkey Visibility (Byte?)
- `80145120`: Button Input (32 bit bitmask)
- `8055399C`: Next Level (Computed on goal) (Short16)
- `80553991`: Current Level (First byte) (Byte)
- `8055399E`: Current stage id (Short16)
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
- `804724B8`: Physical Ball Size (Float32)
- `803E4878`: Visual Ball Size (Float32)
- `805D48F8`: Start of unlock entries for levels of challenge mode (Sequence of bytes) (loaded at least in most of main menu and challenge mode)
- `804C3F70`: Pointer to special struct (8062a294 at least in main menu)
  * Struct at 0x0: Whether Master is unlocked
  * Struct at 0x1: Max number of lives you could start with (if 3, menu for selecting number of lives doesn't show up)
  * Struct at 0x4: Number of play points
- `805D490C`: 0x1C plus the location of the current cm entry (Word32)
- `805D4910`: Stores jump distance at some points (Word32)
- `80553992`: Also stores jump distance at some points (Word32)
- `80553970`: A special bit field that tells us some state about Challenge Mode, like whether we have entered a goal (read function 80313660 for more details)
- `805D4914`: Seems to store which mode we are in. 0x1 if Practice Mode (Word32)
- `805D4918`: Level number in Practice Mode (Word16)
- `805D491A`: Practice Mode difficulty indicator value (Word16)
- `805D491C`: Practice Mode difficulty indicator bit field (Word32)
- `8054DC44`: Difficulty Indicator value when a set of levels is started (Word32)
- `8054DC48`: Difficulty Indicator bit field when a set of levels is started (Word32)
- `803DDE18`: Value related to camera turn rate and level tilt
- `803DDE74`: Camera near clipping Z
- `803DDE78`: Camera far clipping Z
- `803DDE98`: Camera FOV (Double?)
- `803DDEA8`: cameraAng - targetCameraAng multiplier (Double) - Setting this higher makes the camera turn far less, and setting it lower makes the camera constantly turn at the max turn rate until it reaches the goal angle
- `803DDEC0`: Camera height (Relative to ball) (Double)
- `803DDED0`: Camera distance from ball (Double)
- `803DD600`: Beginning of constants listing
- `803DD6B0`: On-screen draw size of the pause menu framebuffer (https://media.discordapp.net/attachments/375039021442662400/474455418031177749/unknown.png / https://media.discordapp.net/attachments/375039021442662400/474455476109574145/unknown.png)
- `803DDC18 - 803DDDDC`: Large section of strings
- `802915F4`: Camera currentAngle - targetAngle multiplier is read here
- `8028353C`: Calls to the main camera
- `80291470`: Main camera function
- `8054E076`: One byte representing camera state (1 (dec) = SMB 1 style camera, 75 (dec) = SMB 2 style camera, and there's a lot more (everything from 1 to about 105 - a few are duplicates))

## Difficulty Indicators

If 6th bit of bit field is set, we selected Master from main menu

If 8th bit of bit field is set, we are playing Master Extra

If 27th bit of bit field is set, we are playing Master

If 28th bit of bit field is set, we are playing the Extra stages of a difficulty

If value is 0, we are in Beginner

If value is 1, Advanced

If value is 2, Expert

## Ball Struct offsets

- `805BC9A0`: Player 0 struct start - main player
- `805BCB50`: Player 1 struct start
- `805BCD00`: Player 2 struct start
- `805BCEB0`: Player 3 struct start
- `805BD060`: Player 4 struct start
- `805BD210`: Player 5 struct start
- `805BD3C0`: Player 6 struct start
- `805BD570`: Player 7 struct start

## Timer Pre Restart

- `805E94C8`: Ball red (Byte8)
- `805E94C9`: Ball green (Byte8)
- `805E94CA`: Ball blue (Byte8)
- `805E9508`: Ball speed (Int32)
- `805E950C`: Flash speed (Int32)
- `805E9510`: Flash pos? (Int32)
- `805E9538`: Ball angle (Short16)

## Timer After Restart

- `805E93F8`: Ball red (Byte8)
- `805E93F9`: Ball green (Byte8)
- `805E93FA`: Ball blue (Byte8)
- `805E9438`: Ball speed (Int32)
- `805E943C`: Flash speed (Int32)
- `805E9440`: Flash pos? (Int32)
- `805E9468`: Ball angle (Short16)

