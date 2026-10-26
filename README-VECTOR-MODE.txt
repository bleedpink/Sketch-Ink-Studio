Sketch & Ink Studio — Vector Mode milestone

New: SVG-based editable vector objects per frame: Select/move, Pen path, Rectangle, Ellipse, Text, duplicate/delete, SVG export. Vector object data is saved in .sketchink project.json under the `vector` property. Older .sketchink projects open with an empty vector layer and retain their raster artwork.

Host the contents of this folder on HTTPS (or use a local static server). Keep backups of existing .sketchink projects. This is an initial vector mode: node-level Bézier editing, resize handles, vector keyframe interpolation, and raster-to-vector tracing are future work.


Vector nodes milestone: use Nodes to drag individual path points. Double-click a path segment to insert a node; Alt-click a node to remove it (paths retain at least two nodes). The Objects panel selects vector objects; right-click an object entry to rename it. Paths are rendered with smooth cubic interpolation between editable anchor points.
