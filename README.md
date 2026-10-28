# SAOMCZHPACK — Resource pack release repository

This repository is the asset-download source for the community-made SAO Minecraft localization project. Text translations and updater code live at https://github.com/ga200604101111/SAOMCZH.

## Files

- pack-version.json: versioned metadata for resource-pack downloads, sizes, SHA-256 and GitHub Release URLs.
- GitHub Releases v1.0.0 draft: one complete SAO_TW_v9.zip and one SAO_ZH_v12_support.zip. There is no need to split the 303.5 MB main pack.
- Runtime updates: download only changed files, verify SHA-256, keep the currently open ZIP during play, activate the new ZIP on next launch, retry cleanup of locked retired files.

## Status

resource_packs.available is false until Release is published. Draft assets are not publicly downloadable. Confirm redistribution permissions for third-party assets before making the Release public or changing the availability flag.

## Copyright and permissions

The archive contains language overrides, textures, large MSDF images and typefaces from several modules. Inclusion here does NOT mean original authors granted redistribution rights. No original mod JAR files are part of this repository.


## v1.0.1 open-font candidate

The new unreleased candidate replaces all three Windows-specific proprietary font files and rebuilds Chinese MSDF glyph atlases from OFL-licensed Noto Sans CJK. The main ZIP and matching support ZIP are preserved in a private draft Release until full copyright and real-game visual verification.

Do not publish the old v1.0.0 ZIP because it still includes Microsoft/DynaLab font material.
See FONT_RIGHTS_NOTICE.md and RELEASE_NOTES_v1.0.1_draft.md.
