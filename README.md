# CC0 Models — Open Source 3D Assets (GLB)

**From [Polygonal Mind](https://www.polygonalmind.com/) — CC0-licensed 3D assets, converted to GLB for easy use everywhere.**

This project turns the original [Polygonal Mind Open Source Initiative](https://github.com/PolygonalMind/initiative-opensource-release) into a **GLB-first**, easy-to-use asset repo: one place to find and drop CC0 environments, props, and scenery into games, web, and open source projects. **We focus only on 3D assets.** For avatars in VRM format (ready for VR, Vtubing, games), see **[open-source-avatars](https://github.com/ToxSam/open-source-avatars)** — a curated registry of free VRM avatars.

---

## What this repo is

- **Source:** [PolygonalMind/initiative-opensource-release](https://github.com/PolygonalMind/initiative-opensource-release) — CC0 character packs, asset packs, and The Sandbox packs (FBX, Unity, VXA/VXM, etc.).
- **Goal:** Make those assets **easier to find and use** by converting them to **GLB/glTF**: no Unity or custom pipelines required, just drop the models into your project.
- **Result:** Curated GLB files in the **`projects/`** folder, one subfolder per pack (e.g. `projects/medieval-fair`, `projects/chromatic-chaos`).

---

## Process

1. **Downloaded** the packs from the original repo.
2. **Batch-converted** FBX (and other supported formats) to GLB using **Blender** (scripts + manual ToExport → GLB workflow).
3. **Manual curation:** materials consolidated, textures resized where needed, unused slots removed, naming cleaned up, colliders wired where relevant. So what you get is “ready to use,” not raw export dumps.

---

## Conversion status

| Status | Packs |
|--------|--------|
| ✅ **Done** | 18 packs (XYZ, ABM, Avatar Garden, CA World, Chromatic Chaos VHS, Cryptoavatars Retro Booth, Crystal Crossroads, LowPolyStore ×3, Medieval Fair, Momus Park, South DCL ×3, The Avatar Show, Tomb Chaser 1 & 2) |
| 🔄 **In progress** | Avatar Webcam (scenario-based; each FBX = full environment) |
| ⬜ **Todo** | Babylon, Dethrone, Underworld (The Sandbox packs — VXA/VXM format) |

So far, **all converted packs are done** except **Babylon**, **Dethrone**, **Underworld**, and **Avatar Webcam**.

---

## Numbers (what you see on GitHub)

- **~991 GLB files** in total across all converted projects.
- **~2.1 GB** total size for the visible repo (the **`projects/`** folder and root files). This is GLB-only output — no source FBX, Unity projects, or art repos, so the repo stays focused and smaller than the full original release.

---

## About Polygonal Mind

[Polygonal Mind](https://www.polygonalmind.com/) is a Zaragoza-based creative studio (est. 2015) that designs environments, avatars, wearables, and experiences for the metaverse. Their Open Source Initiative released a big chunk of their internal work under **CC0** — from 100 Avatars and XYZ figurines to Decentraland Tomb Chaser games, VRChat spaces, Virtual Market booths, and The Sandbox worlds (Babylon, Dethrone, Underworld). This repo is a GLB-focused, easier-to-consume slice of that legacy.

---

## Repository layout (on GitHub)

- **`projects/`** — One folder per pack; each contains the GLB files (e.g. `projects/trash-polka/`, `projects/ca-world/`).
- **`License.md`** — CC0 and usage terms.
- **`docs/`** — In a full local clone, project notes and the original Polygonal Mind README are in `docs/` (this folder is not published to the public repo).

---

## License

CC0. See [License.md](License.md). Same spirit as the [original initiative](https://github.com/PolygonalMind/initiative-opensource-release) — use, modify, distribute, no attribution required.
