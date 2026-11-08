# caddie-courses

Ready-made course packs for Caddie, my Galaxy Watch golf GPS app.

Each `packs/<key>.zip` holds one course exactly as the watch stores it: `course.json` (hole layout, green front/middle/back, heights, check notes) and one aerial photo per hole (`h01.jpg` ...). The watch downloads the pack in a few seconds instead of building the course itself, and falls back to the normal download when there's no pack.

`packs/index.json` lists the courses and when each pack was built.

Course data: OpenStreetMap contributors (ODbL), with some greens and tees traced by hand. Photos: NGI aerial imagery via aerial.openstreetmap.org.za. Heights: Open-Meteo.

Packs are rebuilt from the tools in the Golf App folder (tools/check, `LayoutsKt` then `PhotosKt`) whenever green fixes change.
