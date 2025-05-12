---
layout: page
title: Research
permalink: /research/
---

My thesis work models the time averaged behavior of the Arctic Ocean's Beaufort Gyre.
It's a near axisymmetric wind driven gyre underneath a dynamic sea ice cover and
surrounded by active shelf seas. The combination of a simple geometry with complex
components can produce interesting models!

### Resolving under ice mesoscale eddies
One such model simulates the under ice mesoscale eddy field with high resolution flat bottom channel simulations in MITgcm. This model enforces state estimate density gradients by restoring channel mean fields to the target. The custom channel mean restoring is MPI friendly, allowing long integrations of high res mixing. The input files, including the modified restoring, are available in a Github repo ([link][amb-repo]).

Below are snapshots of the sea ice concentration and vorticity field produced by the model. Each simulation is represented by a row in the grid, with that run's initial sea ice concentration denoted to the right. Sea ice concentration is in the first column,  and vorticity at three depth levels are in the other columns. Even with a high concentration sea ice cover applying heavy drag, the Beaufort Gyre density structure produces a steady mesoscale eddy field underneath.

{: style="text-align: center;" }
![amb-vorticity-snapshots](/assets/figVortSnapshots-FullGrid.png){: width="90%"}


[amb-repo]: https://github.com/hmason13/ArcticMiddepthBI