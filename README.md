# CubiX Client

CubiX Client is a custom Minecraft: Java Edition launcher written in Java and JavaFX.

Features:
- launches official Minecraft versions (files are downloaded from Mojang's official servers)
- optional Fabric support and performance mods from Modrinth
- local skins and capes in offline mode
- sign in with a Microsoft account (device code flow) to play with a purchased copy of the game

Authentication: the launcher uses the Microsoft device code flow
(Microsoft -> Xbox Live -> XSTS -> Minecraft Services). Tokens are stored
only on the player's own computer and are never sent anywhere else.

This is a hobby project and is not affiliated with Mojang or Microsoft.
