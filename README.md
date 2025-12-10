# Dvorak Extended keyboard layout

Designed to accommodate:

- denoting long and short vowels with macron, breve diacritics
- IAST transcription of Sanskrit, Indic languages
- IPA vowel transcription

## Install

Requirements: Mac OS

Copy bundle to user keyboard layout directory:

```
cp -r dv-ext.bundle ~/Library/Keyboard\ Layouts/
```

Restart computer and add `dv-ext` as input source (language: English)


## Layers

- `a`/`¯` -- macron
- `e`/`´` -- aigu
- `u`/`˘` -- breve
- `v`/`ˇ` -- caron
- `6`/`^` -- circumflex
- `` ` `` -- grave
- `/` -- slash
- `-` -- "lower" inspired by Planck keyboard "lower" and "raise"
  - lax vowels; syllabic diacritics: primary, secondary stress, long, half-long

Based on Apple dead-key layer mechanic.

Created with [Ukelele](https://software.sil.org/ukelele/)
