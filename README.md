<p align="center">
  <img src="Andys-Automatic-Doors-Hero-16x9-FINAL.png" alt="Andy's Automatic Doors" width="100%">
</p>

# Andy's Automatic Doors

**Walk up. Walk through. Your vanilla entrance handles itself.**

Andy's Automatic Doors adds configurable proximity opening and closing to individual vanilla doors, fence gates, and trapdoors in Minecraft Bedrock. It is a focused vanilla-plus improvement: no custom blocks, models, recipes, textures, or experimental gameplay.

**Current release:** 0.1.1  
**Download:** [Andys_Automatic_Doors_0.1.1.mcaddon](Andys_Automatic_Doors_0.1.1.mcaddon)  
**SHA-256:** `C4DD8BC556D3CD5C37281C9EB6029245461F4CFC93F411BC5BDDFEBDE914947B`

Minecraft Bedrock **26.30 or newer** is required. Cheats, commands, and experimental gameplay toggles are not required. Standard graphics and Vibrant Visuals are supported.

See the [project wiki](https://github.com/CharlesJGantt/Andys-Automatic-Doors/wiki) for the complete player guide.

## Features

- Opt-in automatic opening and closing for individual vanilla doors, fence gates, and trapdoors
- Two-block approach zones at the front and rear of doors and gates; one-block perimeter for trapdoors
- Single open → exit → close cycle, avoiding repeated movement or sound while passing through
- Redstone-aware closing: powered entrances remain open
- Per-entrance controls with a vanilla stick renamed `DoorControl`
- Operator-only global controls with `AdminDoorControl`
- Multiplayer, Realm, and server ready
- Secure optional compatibility with Andy's Locks & Keys 0.11.3+

## Install

1. Download and open `Andys_Automatic_Doors_0.1.1.mcaddon` with Minecraft Bedrock.
2. Activate **Andy's Automatic Doors [BP]** in the desired world. The linked Resource Pack activates with it.
3. Rename a vanilla stick exactly `DoorControl`.
4. Crouch and use it on a supported entrance, then enable **Proximity**.

Back up important worlds before installing or updating an add-on. Console players can import on Windows or mobile, upload the prepared world to a Realm, then join from their console.

## Controls

Use `DoorControl` while crouching on a supported entrance to configure that entrance. For a single door, stand at either visible face while configuring it; this calibrates its front/rear approach axis and prevents side activation.

Operators can use a stick named `AdminDoorControl` while crouching, or run `/scriptevent andyautodoors:admin settings`, to open the world-wide enable setting.

## Locks & Keys compatibility

Andy's Automatic Doors never bypasses a lock. With Andy's Locks & Keys 0.11.3+ installed, a locked automatic entrance is opened only after Locks & Keys applies its normal owner, key, group, shared-player, and public-access rules. If authorization is unavailable or denied, the entrance remains closed.

See the [project wiki](https://github.com/CharlesJGantt/Andys-Automatic-Doors/wiki) for the complete player guide and troubleshooting information.
