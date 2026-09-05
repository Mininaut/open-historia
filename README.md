# Province-border visual verification

Before (left) and after (right), overview (top, z5.5) and local detail (bottom, z8).

Captured from the actual `src/Game/Map/Nations.jsx` component in Chromium/MapLibre, using a geographic subset of the shipped default scenario around Turkey/Syria. The before panels restore the beta baseline province layer paint/minzoom; all other layers, geometry, camera positions and colors are identical. This is a map-layer harness with a plain background, not a full-game screenshot or the user's historical save. Country borders remain visible and fill-based province picking was checked while outlines were hidden.

The image is kept on this separate evidence branch to avoid adding screenshot binaries to the code PR.
