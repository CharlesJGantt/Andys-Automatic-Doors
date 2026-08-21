# Andy's Automatic Doors v0.1.1

Patch release: single-door proximity is now calibrated from DoorControl's actual front/rear position, eliminating side activation caused by Bedrock's unusual door-direction state.

- Opt-in per-entrance control through `DoorControl`
- Global operator control through `AdminDoorControl`
- Redstone-aware automatic close
- Standard graphics and Vibrant Visuals ready
- Secure optional compatibility with Andy's Locks & Keys 0.11.3+
- Existing single-door settings are reset once so they can be calibrated again; gate and trapdoor settings are retained.

Import the included `.mcaddon`, activate the linked packs, then configure the entrances you want to automate.
