# SAOMCZHPACK v1.0.3 — Broader Chinese Glyph Coverage & Compact HUD Stats (Draft)

**Private draft, do not publish until third-party resource rights and live visual rendering are reviewed.**

Main ZIP: SAO_ZH_Pack_v1.0.3_full_cjk_compact_stats_candidate.zip
Support ZIP: SAO_ZH_v12_support.zip

### Changes from v1.0.2

- Replaces the 6,733-character Noto TC fallback subsets with much broader, renamed regular/bold static Noto Sans CJK TC fonts (44,813 mapped codepoints each).
- Retains the existing 26 optimized MSDF font atlases for common text, with the complete Noto CJK fonts as a fallback for rare Chinese, simplified Chinese and other supported codepoints.
- Vanilla Minecraft font mode remains vanilla/Unifont, and Work Sans mode remains Work Sans + Noto CJK for Chinese.
- Shortens selected SAOUI stat labels to 技暴率, 技暴傷, 暴率, 暴傷, 攻速, 移速, 投射傷, etc. without affecting gameplay text or numeric values.
- The SAOMCZH GitHub translation table is updated independently to zh_tw version 1.0.2.

### Validation

- Scanned 10,389 in-pack / dynamic translation strings: 2,020 unique characters; **zero missing CJK codepoints** from the full Noto fallback in the reviewed set.
- Candidate ZIP CRC, unchanged image atlases, correct font-mode references and full font metadata passed.
- V12 offline native integration passed.
- This does NOT mean support for all Unicode glyphs or all untranslated server strings.
- Live Minecraft visual/font-mode testing is pending.

### Licensing

- Chinese font binaries and derived MSDF additions use Noto Sans CJK TC (SIL OFL 1.1), with license text included in the ZIP.
- The original private v9 pack and its Windows-specific glyph materials are preserved only for local reference and should not be published.
- Remaining third-party assets, copyright notices, trademarks and source-text redistribution permissions still require review.
