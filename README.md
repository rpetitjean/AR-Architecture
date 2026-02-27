# Architectural Model Viewer Template

This template is designed for architects to easily showcase their 3D projects using the powerful [model-viewer](https://modelviewer.dev/) web component.

## How to Use


## Add Your Models (Quick Start)

1. Put your `.glb` files in the `model` folder (all lowercase).
2. In `index.html`, add each model to the `models` array like this:
   `{ src: 'model/YourModel.glb', title: 'Your Model Name' }`
3. (Optional) Change the `<model-viewer>` `src` to your default model.
4. Keep each model under 20MB and use low-res textures for fast loading.


### 3. Why GLB?
- `.glb` is the binary version of glTF, designed for fast loading and compact size.
- It is the standard for web-based 3D (WebGL) and is supported natively by model-viewer.
- Other formats (OBJ, FBX, etc.) are not supported directly in browsers.

### 4. Licensing
- This template is MIT licensed: you can use, modify, and share it freely.
- The [model-viewer](https://modelviewer.dev/) library is under the **Apache-2.0** license. This means:
  - You can use it in commercial and personal projects.
  - You must not remove the original copyright/license.
  - See https://www.apache.org/licenses/LICENSE-2.0 for details.

## Resources
- [model-viewer documentation](https://modelviewer.dev/)
- [GLB format info](https://www.khronos.org/gltf/)

---

**Made for my architect friend to make 3D web presentation and Augmented Reality displays easy!**
