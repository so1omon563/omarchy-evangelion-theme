# Wallpaper artwork and provenance

All seven wallpapers are original prompt-generated outputs created specifically
for this project with OpenAI's image-generation tool on 2026-08-30. None is a
downloaded stock image, extracted animation frame, or third-party wallpaper.

The distributed files are WebP re-encodings of those original PNG outputs.
They retain the original pixel dimensions; the hashes below identify the WebP
files currently distributed in `backgrounds/`.

| File | Pixels | SHA-256 | Art direction |
|---|---:|---|---|
| `backgrounds/1-nerv-command.webp` | 1672×941 | `e73dbe32021465daf8d28ab0ddff3448dc2989e6f2e987e774d90618978f6479` | Red NERV command insignia, dark tactical framing |
| `backgrounds/2-eva-unit-01.webp` | 1672×941 | `8e89f5df1de6c3431f60159423993da37c02e6c241c3ac025cab4dd4c3633322` | Purple/green Unit-01 launch-bay portrait |
| `backgrounds/3-magi-tokyo3.webp` | 1672×941 | `ce8784d549f46ca923ce8760a401a345df293c32785bd36d9642da444e4df002` | Three MAGI-like supercomputer monoliths above Tokyo-3 |
| `backgrounds/4-angel-alert.webp` | 1672×941 | `226a5977bad7fb7a0b7e4e67c194d09c5c7463d86ba2c9a869c8201433e637f1` | Abstract Angel alert over a night skyline |
| `backgrounds/5-eva-unit-00-prototype.webp` | 1920×1080 | `c2f55b2fce5d930050b01fb92128ca123e12c9f8f24155ec6b23ad497139901f` | Yellow/orange prototype armor and restrained blue optics |
| `backgrounds/6-eva-unit-00-refit.webp` | 1920×1080 | `438d97d7b6d2019db6228e9c44799daa194268e5d1cc52dca14fce12fa83cf74` | Blue/white refit armor and clinical launch-bay light |
| `backgrounds/7-eva-unit-02.webp` | 1920×1080 | `a286c7242ad14d23af7b5d9c8b3b7ebd6ef38aeb2452e4bc98e7981a71049cf4` | Red/orange production armor and warning accents |

## Generation record

- Creator/operator: repository owner, assisted by Codex
- Tool: OpenAI image generation
- Purpose: original 16:9 desktop wallpaper set for this Omarchy theme
- Shared direction: dark command-center atmosphere, right-weighted subjects,
  usable negative space, and coordinated EVA palettes
- Third-party source images: none distributed in or copied into this set

Files 5–7 used file 2 only as an in-session style and composition reference.
They were generated as new images, not edits of file 2. Prompts prohibited copied
animation frames, watermarks, and signatures.

The hashes above identify the audited release assets and are duplicated in
`backgrounds.sha256` for automated validation. From this directory, run
`sha256sum --check backgrounds.sha256` to detect later replacements.
