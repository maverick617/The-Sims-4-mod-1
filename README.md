# Sims 4 Mod Project

An open-source starter project for a The Sims 4 custom content or mod package.

> This is an unofficial fan-made project. It is not endorsed by or affiliated with Electronic Arts, Maxis, or The Sims.

## Project Goal

This repository is designed to keep a Sims 4 mod project clean, documented, and easy to share on GitHub.

You can use it for:

- CAS custom content, such as clothing recolors
- Build/Buy custom content, such as furniture recolors
- Tuning mods, such as traits, interactions, careers, or recipes
- Script mod experiments, if the project grows later

## Repository Structure

```text
.
├── assets/              # Original source assets you created
│   ├── textures/        # PNG, PSD, XCF, or other editable texture files
│   ├── meshes/          # Blender or mesh source files
│   └── icons/           # Original icon artwork
├── docs/                # Design notes, tutorials, and release notes
├── packages/            # Built .package files for testing or releases
├── src/                 # Tuning XML, scripts, or exported mod source files
├── tools/               # Helper scripts, if needed
└── README.md
```

## Installation

1. Download the latest `.package` file from the GitHub Releases page.
2. Move it into your Sims 4 Mods folder:

   ```text
   Documents/Electronic Arts/The Sims 4/Mods
   ```

3. In The Sims 4, enable:

   ```text
   Game Options > Other > Enable Custom Content and Mods
   ```

4. Restart the game.

## Development Workflow

Recommended beginner workflow:

1. Create or clone a base item in Sims 4 Studio.
2. Export the texture, mesh, or tuning file.
3. Save editable source files in `assets/` or `src/`.
4. Import changes back into Sims 4 Studio.
5. Save the built `.package` into `packages/` for local testing.
6. Test in game before creating a release.

## Copyright And Asset Rules

To keep this project safe to publish:

- Use original artwork, textures, names, icons, and descriptions whenever possible.
- Do not include paid custom content made by other creators.
- Do not include copyrighted brand logos, celebrity photos, anime/game characters, or copied artwork unless you have permission.
- Do not present this project as official EA or Maxis content.
- Credit contributors clearly.

See [docs/COPYRIGHT.md](docs/COPYRIGHT.md) for more detail.

## License

Project code and documentation are licensed under the MIT License.

Original visual assets in `assets/` are licensed under CC BY 4.0 unless a specific asset says otherwise.

The Sims, The Sims 4, EA, and Maxis are trademarks of their respective owners.
