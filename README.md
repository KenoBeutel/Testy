# µSAM² click segmentation demo

An interactive demo of the µSAM² annotation workflow, in a single HTML file with no dependencies.

- **Left click** on a cell adds a positive point. Each clicked cell becomes its own object with its own colour.
- **Right click** adds a negative point and removes a region from the object it lands in.
- **Commit** (Enter) keeps all objects in progress, **Segment all** (A) segments every cell, **Undo** (Z) steps back.
- On touch screens, switch between positive and negative taps below the image.

Three synthetic micrographs are included: fluorescence (yeast), brightfield (rods) and phase contrast (colony).

The micrographs are generated in the page and the masks are simulated. No model runs here; the demo shows how annotating with µSAM² feels.

Open `index.html` in a browser, or enable GitHub Pages for this repository to host it.
