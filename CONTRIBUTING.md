# Contributing to Things and That

Thank you for contributing to this asset repository! This guide will help you organize and submit assets properly.

## Asset Organization

### File Naming Conventions

Use lowercase letters with hyphens to separate words:
- ✅ `player-character-idle.png`
- ✅ `background-music-forest.ogg`
- ✅ `dialogue-intro-scene.txt`

Avoid:
- ❌ Spaces: `player character idle.png`
- ❌ Special characters: `player@character#idle.png`
- ❌ Mixed case: `PlayerCharacterIdle.png`

### Directory Structure

Place assets in the appropriate subdirectory:

```
assets/
├── art/
│   ├── sprites/        # Characters, objects, animations
│   ├── textures/       # Backgrounds, materials, patterns
│   ├── ui/            # Interface elements, buttons, icons
│   └── concepts/      # Concept art, reference materials
├── text/
│   ├── scripts/       # Dialogue, cutscene text
│   ├── descriptions/  # Item/character descriptions
│   ├── lore/         # Story, world-building content
│   └── metadata/     # Configuration, data files
└── audio/
    ├── music/        # Background music, themes
    ├── sfx/          # Sound effects, short clips
    ├── voice/        # Voice acting, narration
    └── ambient/      # Environmental sounds
```

## File Format Guidelines

### Art Assets
- **Sprites/UI**: PNG with transparency
- **Textures**: PNG or JPEG
- **Source files**: Keep PSD, XCF, SVG when possible

### Text Assets
- **Scripts**: TXT or MD format
- **Data**: JSON, YAML, or XML
- **Encoding**: Always use UTF-8

### Audio Assets
- **Music**: OGG Vorbis or MP3
- **SFX**: WAV or OGG
- **Voice**: OGG or MP3
- **Source**: Keep WAV/FLAC masters when possible

## Submission Process

1. Fork the repository
2. Create a feature branch: `git checkout -b add-new-assets`
3. Add your assets to the appropriate directories
4. Remove any `.gitkeep` files from directories you're adding to
5. Update relevant README files if needed
6. Test that your assets work as expected
7. Submit a pull request with a clear description

## Quality Standards

- Optimize file sizes appropriately
- Test assets in target application/game
- Include source files when beneficial
- Follow consistent style within asset categories
- Document any special requirements or usage notes

## Questions?

If you're unsure about where to place an asset or have questions about the organization, please open an issue for discussion.