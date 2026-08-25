# Arc & Aura listing images

Public image host for Depop bulk listing CSVs.

Depop's bulk listing template takes a URL per photo, not a file. These are the
1280x1280 copies those URLs point at. The 4000x4000 masters stay local in
`listing gallery/` and are never pushed here.

Rebuild with `python tools/build_hosting.py`.

One folder per product, photos numbered in upload order. 1.jpg is the cover.
