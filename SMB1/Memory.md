Memory Addresses
================

- `80206BFC`: Max stage tilt (For the current stage play - Affects visual display and physics - https://puu.sh/AJA3r/34bd26155e.webm | Float32)
- `802F36B8`: Max stage tilt (For all future stage plays - writes to `802F36B8` on stage start - Affects visual display and physics - https://puu.sh/AJA3r/34bd26155e.webm | Float32)
- `80206BF8`: Ball control state (Byte8)
- `80206BF0`: Z tilt (Short16)
- `80206BF2`: X tilt (Short16)
- `80206BE0`: Off-balance timer (Int32)

