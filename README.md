# Patch Codex Pet

Patch is a custom Codex pet package.

## Install

Copy the package folder to your Codex pets directory:

```powershell
Copy-Item -Recurse -Force ".\pets\patch" "$env:USERPROFILE\.codex\pets\patch"
```

In Codex, refresh the pet list and select:

```text
custom:patch
```

## Files

- `pets/patch/pet.json` - Codex pet manifest
- `pets/patch/spritesheet.webp` - animated pet spritesheet
