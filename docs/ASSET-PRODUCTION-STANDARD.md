# Asset Production Standard

## Production exports

- Use PNG for raster assets requiring alpha transparency.
- Preserve RGBA color data where transparency is required.
- Use sRGB unless a print workflow explicitly requires another profile.
- Trim unnecessary empty canvas while preserving intentional padding.
- Keep the subject centered unless the asset is designed for directional placement.
- Check exports against both light and dark backgrounds.

## Source files

- Preserve editable source files separately from production exports.
- Use descriptive layer names.
- Keep text editable until the final export stage.
- Do not overwrite the only editable source with a flattened copy.

## Quality checks

Before committing an asset:

1. Confirm the filename follows `docs/NAMING-STANDARD.md`.
2. Confirm transparency is real alpha transparency, not a white or checkerboard background.
3. Check for white, black, or colored edge halos.
4. Verify the image is not unintentionally cropped.
5. Confirm the asset belongs in the selected category.
6. Remove metadata that exposes private working information when appropriate.

## Proof sheets

Proof sheets are review material, not production assets. Keep them outside production directories. Only approved individual exports belong in the reusable asset library.
