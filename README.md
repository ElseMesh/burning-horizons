# LOZ-derived cave world content

This repository contains the portable cave world package and its source data.
It is not a standalone application or buildable game. ElseMesh imports it as
the `worlds/loz-underneath` Git submodule for the two-world portal example and
integration fixture.

The source document, presentation, cave GLB, ambience recording, derived
collision proxies, and content-addressed assets are kept together here. Runtime
behavior is described by versioned world components and implemented by
ElseMesh. The exporter and validators live in the ElseMesh engine repository;
run `npm run export:loz-underneath` from an ElseMesh checkout to regenerate the
package.
