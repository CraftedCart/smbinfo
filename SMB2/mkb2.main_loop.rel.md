mkb2.main_loop.rel Addresses
============================

- `2023BC`: Ball acceleration constant (Float)
- `2023B8`: Ball radius (Float | Default 0.5)
- `2023C0`: Ball restitution (Float | Default 0.5)
- `174778`: Ball visual size
- `16E738`: Music list (More info: https://pastebin.com/M0GwVTAf)
- `1E5298`: Lighting data (Detailed below)
- `204E48`: Stage theme list (421 themes, starting at index 0 | Theme IDs here: https://pastebin.com/WAJ9vHWa)
- `2075B0`: Challenge mode entries
- `20B448`: Story mode entries (More info: https://craftedcart.github.io/SMBLevelWorkshop/documentation/index.html?page=modifyingStageOrder)

## Other curiosities

- Modifying `2668C` to `60000000` makes the timer run while paused
- Modifying `27438` to `60000000` makes the timer infinite
- Modifying `40210` sets the dipswitch. `38000003` for debug

## Lighting data

- More info: https://pastebin.com/uKdK3U2v

- `00` Plain 0: `1E5298`
- `01` Plain 1: `1E52E0`
- `02` Jungle 1: `1E5328`
- `03` Water 1: `1E5370`
- `04` Night: `1E53B8`
- `05` Sky: `1E5400`
- `06` Space 1: `1E5448`
- `07` Sand: `1E5490`
- `08` Ice: `1E54D8`
- `09` Storm: `1E5520`
- `0A` Bonus 1: `1E5568`
- `0B` Unk SMB1: `1E55B0`
- `0C` Unk SMB1: `1E55F8`
- `0D` Unk SMB1: `1E5640`
- `0E` Unk SMB1: `1E5688`
- `0F` Master: `1E56D0`
- `10` Ending: `1E5718`
- `11` Lava: `1E5760`
- `12` Water 2: `1E57A8`
- `13` Jungle 2: `1E57F0`
- `14` Park: `1E5838`
- `15` Pot: `1E5880`
- `16` Space 2: `1E58C8`
- `17` Electric: `1E5910` (Has special rules)
- `18` Gear: `1E5958`
- `1A` Bonus 2: `1E59E8 (Has special rules, but they don't apply to custom yet)`
- `19` Bubbly: `1E59A0`
- `1B` Soccer: `1E5A30`
- `1C` Bowling 2: `1E5A78`
- `1D` Target 2: `1E5AC0`
- `1E` Billiards 2: `1E5B08`
- `1F` Boat: `1E5B50`
- `20` Whale: `1E5B98` (Has special rules)
- `21` Golf: `1E5BE0`
- `22` Pot Fight: `1E5C28`
- `23` Village: `1E5C70`
- `24` Bubbly Cutscene: `1E5CB8`
- `25` Park Cutscene: `1E5D00`
- `26` Gear Cutscene: `1E5D48`
- `27` Water 2 Cutscene: `1E5D90`
- `28` Ocean Surface Cutscene: `1E5DD8`
- `29` Bowling Cutscene: `1E5E20`
- `2A` ???: `1E5E68`
- `2B` ???: `1E5EB0`
- `2C` ????????: `1E5EF8`

