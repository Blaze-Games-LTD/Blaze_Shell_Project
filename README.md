# Blaze Shell Project

A starter Unreal Engine 5 project from **Blaze Games**. It's based on Epic's Third Person Blueprint template and set up to open in the template's **Side Scroller** variant, ready to build on.

## Requirements

- **Unreal Engine 5.8**
- **[Git LFS](https://git-lfs.com/)**. The project's `.uasset` and `.umap` files are stored with Git LFS.

## Getting the project

**GitHub Desktop:** go to **File → Clone repository** and enter `Blaze-Games-LTD/Blaze_Shell_Project`. GitHub Desktop downloads the LFS files automatically.

**Command line:**

```bash
git lfs install
git clone https://github.com/Blaze-Games-LTD/Blaze_Shell_Project.git
```

> Clicking **Code → Download ZIP** on GitHub won't give you the real asset files, because it doesn't include the Git LFS content. Clone the repo instead.

## Opening the project

1. Open `Blaze_Shell_Project.uproject`.
2. If you're asked to rebuild or convert the project, check you're using Unreal Engine 5.8.

The project opens on `Lvl_SideScrolling`, which is also the default game map.

## What's included

| Folder | Contents |
|---|---|
| `Content/Variant_SideScroller` | Side-scrolling level, Blueprints, animations, input and UI (the default setup) |
| `Content/ThirdPerson` | The original Third Person level and Blueprints |
| `Content/Characters/Mannequins` | Epic's mannequin characters and animations |
| `Content/LevelPrototyping` | Blockout meshes, materials and interactables |
| `Content/Input` | Enhanced Input actions and touch controls |

This is a Blueprint-only project, so there's no C++ source.

**Enabled plugins:** Modeling Tools Editor Mode (editor only) and Gameplay State Tree. Both ship with the engine.

## Contributing

Close Unreal Editor before you commit. Generated folders (`Binaries`, `Intermediate`, `Saved`, `DerivedDataCache`) are excluded by `.gitignore`.

---

Made by Blaze Games Ltd · [blazegames.net](https://blazegames.net)
