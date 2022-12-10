# Simplex Flower Generator - Three.js/WebGL

A Pen created on CodePen.io. Original URL: [https://codepen.io/jackrugile/pen/LeJowx](https://codepen.io/jackrugile/pen/LeJowx).

Generate flowers with simplex noise! I had a lot of fun making this one and I think it yields some pretty results. Click and drag/mousewheel to manipulate the camera position.

`THREE.MeshLine()` creates meshes with varying line thickness. It's a lot more flexible and customizable compared to `THREE.Line()`. Before creating the meshes, the paths are generated and reflected using `Walker()`s which determine their angle and speed based on simplex noise.

I used the following tools to create this:

- [Three.js](https://github.com/mrdoob/three.js/) - JavaScript 3D WebGL Library by [mrdoob](https://github.com/mrdoob)
- [THREE.MeshLine](https://github.com/spite/THREE.MeshLine) - Mesh replacement for THREE.Line by [spite](https://github.com/spite)
- [simplex-noise.js](https://github.com/jwagner/simplex-noise.js) - A fast simplex noise implementation in JavaScript by [jwagner](https://github.com/jwagner)
- [VariaBoard](https://github.com/jackrugile/variaboard) - A control interface that is a major work in progress by [me!](https://github.com/jackrugile)
