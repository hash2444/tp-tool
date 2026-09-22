# TP Tool

> A teleport tool that only whitelisted players can hold - managed by the server operators.

[![Download](https://img.shields.io/badge/Download-latest%20build-e94560?style=for-the-badge&logo=github&logoColor=white)](../../releases/latest)

Operators decide who may use the **TP Tool** with a whitelist menu. Whitelisted players get the tool automatically (and keep it), everybody else loses it the moment it appears in their inventory. Right-click the tool, pick a player, and after a 5 second countdown you are teleported to that player's current position.

## What it does

- Whitelist managed in-game by operators: `/scriptevent tpdev:menu`
- Countdown teleport (5 s) with a live action-bar - switch to spectator if you want to arrive unseen
- Non-whitelisted players cannot keep the tool: it is removed from inventories and dropped item entities
- The tool can be switched off for operators too

## Download

Download **`TP-Tool-v1.0.6.mcaddon`** from the [releases page](../../releases) (or straight from this repository) and open it - Minecraft imports the packs.

1. Create or edit a world and open **Add-Ons**.
2. Activate the **Behavior Pack** and the **Resource Pack** of this add-on.
3. Requires Minecraft Bedrock **1.20.50 or newer**.

If items are missing in your world, check the world's *Experiments* page and enable *Beta APIs* and *Holiday Creator Features* as a fallback.

New to this? Follow **[SETUP-HELP.md](SETUP-HELP.md)** - it walks you through installing and starting it.

## Dev Book

Every pack of mine carries a small easter egg: craft the **Dev Book** with **9 logs** (any wood type, 3x3 in a crafting table) and right-click it. It opens like a book: page 1 the credits, page 2 what this mod is, page 3 the GitHub links (Minecraft cannot open links, so they are shown as text). It also sits in the creative inventory under *Equipment*.

## Notes

- Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.

![preview](tp-tool.png)

---

Made by **dev:#2444** - [github.com/hash2444](https://github.com/hash2444) - [tp-tool](https://github.com/hash2444/tp-tool)
