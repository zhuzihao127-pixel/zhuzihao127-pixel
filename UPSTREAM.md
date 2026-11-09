# Galaxy Profile source

The generator and its associated tools come from [vinimlo/galaxy-profile](https://github.com/vinimlo/galaxy-profile/tree/ca7706590fe6f3f012b3e63e4ff5d101380f60b2) and are distributed under [GPL-3.0](LICENSE). Fonts are distributed under their respective SIL Open Font Licenses in [assets/fonts](assets/fonts).

This repository adds a profile-specific README, configuration, generated SVGs, and a refresh workflow. Run `pip install -r requirements.txt` and `python -m generator.main` from the repository root to regenerate the SVGs.

The contribution chart supports Simplified Chinese via `stats.locale: zh-CN` in `config.yml`. The default locale is `en`.
