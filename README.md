# DustManifold

A 3D-printable dust-collection manifold port, with the Fusion 360 source
included so it can be modified.

The parts are built around a round port of about 4 in (≈100 mm) outside
diameter. The Fusion 360 design and the `.obj` export are the full model.
The STL files are the individual parts, ready to slice.

## Files

| File | What it is |
| --- | --- |
| `Dust Manifold Port v6.f3d` | Fusion 360 source design. Edit this to change the part. |
| `Dust Manifold Port v6.obj` | Mesh export of the whole model, with groups `Bracket Right`, `Bracket Left`, `Out Right`, `Out Left` and `Body1`. |
| `In Port.stl` | Inlet port: a round collar on a 5.5 in square flange. |
| `Out Left.stl` / `Out Right.stl` | Outlet parts: a flat 1/8 in plate with a round outlet stub standing up from it. |
| `Bracket Left.stl` / `Bracket Right.stl` | Bracket parts: a 1/8 in base plate with a round opening and an upright 1/4 in wall that has two small holes. |

Each Left/Right pair looks like a mirror image: same size, with the features
on opposite sides.

## What the geometry shows

These numbers were measured from the STL meshes. They are approximate
(nominal inch values where they round cleanly), and nothing beyond the
measurements has been confirmed.

- **In Port**: a round collar about 4.0 in (≈101 mm) outside diameter with a
  bore of about 3.6–3.7 in (≈92–94 mm). It sits on a 5.5 x 5.5 in square
  flange with no fastener holes.
- **Out Left / Out Right**: the outlet stub is about 101.6 mm (4.0 in) outside
  diameter at its base and narrows slightly to about 99.8 mm before a rounded
  tip. It is open through the plate with a bore of about 94 mm (3.7 in).
- **Bracket Left / Bracket Right**: the base plate has a round opening of
  about 94 mm (3.7 in). The upright wall has two small holes, about 4–5 mm,
  spaced about 89 mm (3.5 in) apart. They are probably for screws, but that
  has not been confirmed.

## Printing notes

- The design is split into left and right halves so that each part fits on a
  common print bed.
- Approximate part sizes (X x Y x Z):

  | Part | mm | in |
  | --- | --- | --- |
  | Bracket Left / Right | 140.3 x 152.4 x 38.1 | 5.52 x 6.0 x 1.5 |
  | Out Left / Right | 140.3 x 152.4 x 41.3 | 5.52 x 6.0 x 1.625 |
  | In Port | 139.7 x 139.7 x 44.5 | 5.5 x 5.5 x 1.75 |

- To change a part, open the Fusion 360 source (`.f3d`) and export new STLs.

## Not yet documented

- What the manifold mounts to.
- The hose or fitting size it is meant to connect to. The ≈4 in port
  diameter is measured, not a stated fit.
- How the parts go together, and what hardware is needed.
- Recommended print settings (material, layer height, infill, supports,
  orientation).
