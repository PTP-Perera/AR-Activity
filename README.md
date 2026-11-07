# Astral Relics AR Museum

A small Hiro-marker museum exhibit built with A-Frame and AR.js. It displays a
Damaged Helmet model on a rotating pedestal, with a floating color-changing
orb, an animated gold display piece, exhibit labels, and a marker status banner.

## Run the exhibit

The camera needs a secure context. Serve the project from an HTTPS host, then
open its `index.html` URL on a phone and allow camera access. Print or display a
Hiro marker and hold it in view.

- Tap the blue orb to change its color.
- Tap the helmet to toggle its size.

The GLB file must stay alongside `index.html` when hosting the project.

## Model credit and license

The exhibit uses **Damaged Helmet**, a fictional flight helmet model by
**ctxwing**, downloaded from the
[Khronos glTF Sample Assets repository](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/DamagedHelmet).
The repository credits ctxwing for rebuilding and converting the model under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). It also credits
**theblueturtle_** for the earlier version under
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). The earlier
version's non-commercial condition applies; this school exhibit is intended for
non-commercial educational use. The repository notes that the model was
re-exported from Blender for the final glTF 2.0 specification.

## Publish and test

1. Publish `index.html`, `DamagedHelmet.glb`, and this README using Netlify Drop
   or GitHub Pages. Use the resulting HTTPS URL.
2. Open that URL on a phone, grant camera permission, and check that the Hiro
   marker triggers both banner states.
3. Check that the orb changes color and the helmet grows and returns to size
   when tapped.

The project files are prepared for hosting, but an HTTPS deployment and
physical-phone test still need to be completed by the project owner.
