# Constellation packs

Shared modpacks for **MC Constellation**, a private Minecraft launcher for a group of friends.

Each pack is one small file, `packs/<id>/pack.json`: the Minecraft and loader version and the list of mods (with their
version, where to download them, their checksum, and whether they belong on the client, the server or both).
`index.json` lists the packs. The format is described in the launcher's `docs/PACK_FORMAT.md`.

No mod files are stored here: every mod says where to download it from (Modrinth, CurseForge, or the host's launcher).
Packs are published by the launcher; please don't edit them by hand.
