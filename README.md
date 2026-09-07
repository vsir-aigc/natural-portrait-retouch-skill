# Natural Portrait Retouch Skill

Natural Portrait Retouch is a Codex skill for portrait and wedding photo retouching. It captures a practical retouching direction focused on visible quality improvement while preserving identity, skin texture, facial structure, clothing detail, scene intent, and a clean film-inspired color style.

## What It Covers

- Natural but visible portrait refinement
- Facial structure, jawline, under-eye, wrinkle, and neck-line cleanup
- Skin blemish cleanup while preserving believable texture
- Hair flyaway cleanup and natural shine
- Clothing wrinkle cleanup and edge refinement
- Body shaping with realistic proportions
- Scene-aware cleanup that keeps intentional props and set design
- Clear, breathable film color inspired by Kodak Portra 400, Fujifilm Pro 400H, and Superia-style references
- Special handling for food, plants, architecture, backlight, and extreme skin conditions

## Repository Layout

```text
natural-portrait-retouch/
  SKILL.md
  references/
    clear-film-look.md
    sample-look.md
    extreme-backlight.md
    text references
```

## Installation

Copy the `natural-portrait-retouch` folder into your Codex skills directory:

```powershell
Copy-Item -Recurse -Force .\natural-portrait-retouch "$env:USERPROFILE\.codex\skills\"
```

Then restart Codex or refresh available skills.

## Usage

Ask Codex to use the skill when retouching an image:

```text
Use $natural-portrait-retouch to retouch this portrait.
```

You can also describe a specific strength, such as light, standard, or enhanced retouching.

## Notes

This skill describes retouching judgment, quality standards, and prompting direction. It does not replace manual Photoshop work and cannot guarantee exact layer-based edits when the active image tool only supports generative editing. Always review the output against the original image, especially faces, hands, clothing edges, text, jewelry, and background geometry.

The public package intentionally excludes private portrait reference images. If you maintain a private fork, you can add your own licensed or client-approved references.

## License

MIT
