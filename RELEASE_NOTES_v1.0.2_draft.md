# SAOMCZHPACK v1.0.2 — Corrected Dual Font Modes (Private Draft)

### Minecraft / SAOUI menu font selector

- Work Sans: Work Sans for Latin lettering, licensed Noto Sans CJK TC for Chinese, then Minecraft fallback.
- Minecraft: original Minecraft glyphs, including original Unifont fallback for Chinese. No global injection of Noto font. Custom bitmap/icon providers continue to work.
- The menu title is 選單字型, with the native values Work Sans and Minecraft.

### Validation

- Original SAOUI 2.35.0 FontChoice class verified to change saved font preference and reinitialize UI/chat.
- Original resource pack remained unchanged.
- Only assets/minecraft/font/default.json and assets/minecraft/font/uniform.json changed relative to the v1.0.1 open-font candidate.
- SHA-256, ZIP CRC, unchanged font atlas bytes, font provider resolution checks and V12 Agent native offline integration passed.
- Not yet tested visually in the actual running Minecraft client.

### Legal / availability

The candidate is still a private draft pending full review of third-party resources and a live visual/font toggle check. DO NOT PUBLISH until remaining rights are cleared. pack-version.json keeps resource_packs.available=false.
