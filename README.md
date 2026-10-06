# Atom probe tomography: visual lessons

A small static site that teaches atom probe tomography (APT) in eight lessons, using the CAMECA Invizo 6000 as the running example. It is one self-contained file with no build step and no dependencies.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages

1. Create a new repository and add `index.html` and `README.md` to the root.
2. Commit and push to the `main` branch.
3. In the repository, open Settings, then Pages. Under Build and deployment, choose "Deploy from a branch", select `main` and the `/ (root)` folder, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

Lessons are linkable, for example `#lesson-3`.

## What is in the site now

- Lessons 1 to 9, each with a summary, a key idea and a check-yourself question
- Lesson 9: parameter trade-offs demo, material-by-material guidance and a selection checklist
- Interactive demos: field evaporation (2), mass spectrum (3), sequence to depth (4), clickable Invizo 6000 parts and single versus dual laser (5), annular milling (6), points to voxels to isosurface (7), detection efficiency and clusters (8)

## Still to add

Energy barrier, projection magnification, ranging window trade-off, isosurface threshold and voxel size, local-magnification artefact, thermal tail, run-parameter trade-offs, MCP versus delay line, and the electrode-hole diagram. Each is one function in `S` plus one HTML string in `W`.

## Sources and cautions

Instrument figures come from the NUS poster "Invizo 6000 Atom Probe Tomography: Operating principles, specimen preparation, and data analysis" and CAMECA material. The demos are simplified teaching models. Check values against current datasheets before quoting them, and add your own images only if you have the rights to use them.
