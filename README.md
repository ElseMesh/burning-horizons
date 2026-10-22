# Burning Horizons world content

This repository contains the authored UNDERNEATH cave package and its source
assets. It is content data, not a standalone application or buildable game.
It is maintained independently from the ElseMesh engine and the Tidewater
example world.

The source document, presentation, cave GLB, ambience recording, derived
collision proxies, and content-addressed runtime assets are kept together here.
ElseMesh implements the versioned runtime behavior and can load the package as a
separately hosted world. Its exporter and validators live in the ElseMesh engine
repository; set `BURNING_HORIZONS_DIR` to this checkout when using them.
