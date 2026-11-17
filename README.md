# SYNAPSE — Anatomy explorer preview

React / TypeScript / Three.js / Vite. Interactive rotation, zoom, pan, layer visibility, opacity, bilingual search, focus and isolation.

Arteries are red and veins blue in both rendering modes. Nerves, whole skin and male reproductive structures are excluded.

## Run
Node.js 22+. `npm install`, `npm run dev`. Verify with `node --test test.mjs` and `npm run build`.

## GitHub Pages
Set Settings → Pages → Source to GitHub Actions. The included workflow builds and deploys dist. Relative Vite base supports the /synapse/ project path.

## Model attribution & license
BodyParts3D, © The Database Center for Life Science licensed under CC Attribution 4.0 International.

Source: https://dbarchive.biosciencedbc.jp/en/bodyparts3d/download.html
Current official license: https://dbarchive.biosciencedbc.jp/en/bodyparts3d/lic.html
Original OBJ headers state CC BY-SA 2.1 Japan. Converted model assets retain that original attribution and are shared under the original CC BY-SA 2.1 Japan conditions: https://creativecommons.org/licenses/by-sa/2.1/jp/ . The current official license changed to CC BY 4.0 in 2025; both notices are recorded here.

Changes: selected source objects, converted OBJ to GLB, retained original positions and triangles, computed smooth normals. Viewer transforms millimetres to metres and rotates X -90 degrees. Colors are illustrative: artery/vein colors do not indicate oxygenation.

640 objects: 201 bone, 209 muscle, 91 organ segments, 139 vessels. Object counts are not counts of complete organs. Systems remain incomplete; lung parenchyma is absent. No professional medical review. Exploration only, not clinical use.

Source/object IDs, file sizes, hashes and processing: asset-manifest.json. Some descriptions reference OpenStax Anatomy and Physiology 2e, with links in src/details.ts. Three.js, React and Vite use MIT licenses. DBCLS and the referenced authors do not endorse this project.

