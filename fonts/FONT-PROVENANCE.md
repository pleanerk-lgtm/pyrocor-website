# Local font provenance and licences

This static package redistributes local WOFF2 files selected by the Google Fonts stylesheet declared in `client/index.html` for DM Sans and Manrope. The export tool downloads the CSS and font bytes unchanged, then changes only CSS URLs to local `/fonts/` paths.

The authoritative Open Font License text for each family is included below as a separate, unmodified text file.

- **DM Sans**
  - Licence source: https://raw.githubusercontent.com/google/fonts/main/ofl/dmsans/OFL.txt
  - Included licence text: `DM-Sans-OFL.txt`
- **Manrope**
  - Licence source: https://raw.githubusercontent.com/google/fonts/main/ofl/manrope/OFL.txt
  - Included licence text: `Manrope-OFL.txt`

The exact Google CSS response and original font-file responses are retained in the sibling export cache at `cache/fonts/`; the portable source uses the self-contained localized `client/public/fonts/fonts.css`.
