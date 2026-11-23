# Divine carbon atom

Rotate a single three-dimensional structure to see **Aum**, the **traditional swastika**, and **alpha and omega** emerge from four dark-red ribbons. Each view uses the same ribbons on four tetrahedrally arranged surfaces. Open **Probability cloud** to overlay electron probability samples on any of the three perspectives.

## Run it

Download [index.html](./index.html) and open the saved file in a browser with WebGL enabled. The file includes Three.js, OrbitControls, styles, source illustrations and the third-party license. It works offline. For static hosting, serve the repository root, with `index.html` as the entry point. There is no build step.

## Explore

Use the language selector in the header to choose among 21 languages. Translations are embedded in the HTML and work offline. The browser remembers your selection. Arabic and Persian use a right-to-left layout.

| Control | Action |
| --- | --- |
| Drag | Rotate the model |
| Scroll or pinch | Zoom |
| Right-drag or Shift-drag | Pan |
| **1**, **2**, **3** | Select Aum, swastika, or alpha and omega |
| **Start the journey** | Tour the three perspectives |
| **Tetrahedron** and **Orbitals** | Show or hide the frame and the four surfaces independently. Both start visible. |
| **Orbital opacity** | Adjust the transparency of the four surfaces. The default is 22%. |
| **Curve expression** and **Ribbon spread** | Adjust the shared ribbon geometry. The starting values are 103% and 100%. |
| **Probability cloud** | Expand the controls and check **Show probability cloud**. Select any combination of 1s, 2s, 2p<sub>x</sub>, 2p<sub>y</sub> and 2p<sub>z</sub>. Cloud size starts at 100% and cloud opacity at 34%. |
| **Link to tetrahedral lobes** | Align a selected 2p axis with a tetrahedral lobe. |
| **Fine-tune the view** | All four ribbons have cylindrical ends at the centre by default. Uncheck **Cylindrical ribbon ends at the centre** for pointed ends. You can also adjust the roll and tour pace or save a viewing angle. |
| **↓** | Export the current canvas as a PNG |

## Reading the overlay

**Symbols** reconstructs the geometry of the source illustrations. Rotating the tetrahedron changes the projected shape of the ribbons. Their paths and the scale of the surfaces are artistic choices.

The optional cloud samples screened hydrogenic orbitals for the ground-state configuration of neutral carbon, **1s² 2s² 2p²**. Each dot represents a probability sample. With all five layers visible, the three perpendicular 2p directions share the contribution of the two 2p electrons equally, giving a spherical average. The optional paired 2p surfaces mark 10% of each orbital’s peak probability density. [NIST atomic data for carbon](https://physics.nist.gov/PhysRefData/Handbook/Tables/carbontable1.htm)
