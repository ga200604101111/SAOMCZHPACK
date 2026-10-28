# SAOMCZHPACK v1.0.4 — Complete Font Fallback + Compact Stats (Draft)

Private draft. Do not publish yet: real-game visual tests and remaining third-party asset rights are pending.

- Full Noto Sans CJK TC regular/bold font fallback: 44,813 codepoint mappings, both weights.
- All 26 existing MSDF atlases retained for common Chinese text.
- Two font choices: Work Sans (English Work Sans + Noto CJK TC fallback); Minecraft (vanilla Minecraft/Unifont fallback).
- v1.0.4 fixes three private-use alias glyphs U+E900/U+E901/U+E902 (characters 並/中/串). There are 1,345 locale entries using these aliases across the historical language pack. These now render in Minecraft mode through a new small Noto-derived bitmap atlas, without forcing the whole Noto font on the vanilla typeface.
- SAOUI title and dynamic translation labels are shortened (e.g. 技暴率, 技暴傷, 暴率, 暴傷, 攻速, 移速).
- ZIP integrity, original pack preservation, atlas consistency, selected font provider consistency, Noto glyph coverage and V12 native offline integration passed.

This is NOT a guarantee for every Unicode emoji or third-party renderer. Player-written chat remains unmodified by the translation layer; font fallback still applies.
