# Depth Wizard 2 — public tile assets

Image assets for the Depth Wizard 2 (SIH26175) "Choose from Library" catalog. This repo holds
only these release assets and this README; the application code is not published here.

Release [`library-v1`](https://github.com/sancharimouri/depthwizard2-assets/releases/tag/library-v1) contains, per item,
the GeoTIFF tile (`<id>.tif`), a 256 px thumbnail (`<id>__thumb.jpg`) and a 1024 px preview
(`<id>__preview.jpg`). Thumbnails and previews are resized and contrast-stretched: **modified** from the source.

## Sentinel-2 (32 tiles, `sentinel2-*`)
Contains modified Copernicus Sentinel data (2025). Sentinel-2 L2A true colour (B04/B03/B02), 10 m,
cropped to benchmark footprints. Use is governed by the
[Copernicus Sentinel data legal notice](https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice)
(free, full and open access; attribution required).

## Maxar Open Data (6 crops, `vhr-*`)
Imagery © Maxar Technologies (Vantor), Maxar Open Data Program, licensed
[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). **Non-commercial use only.**
Changes: 2048 × 2048 px crops (Sikkim / Darjeeling Himalaya) cut from source scenes
`10300100CF621C00`, `10300100CE8D0400` (2022-03-07) and `1040010073381800` (2022-03-14),
plus the resized thumbnails/previews above.

## DFC2019 (42 tiles, `dfc2019-*`): TEMPORARY
Source: 2019 IEEE GRSS Data Fusion Contest, Track 1 (WorldView-3 RGB, Jacksonville and Omaha;
dataset by Johns Hopkins University Applied Physics Laboratory / IARPA CORE3D). Changes: tiles
re-encoded losslessly (deflate), previews resized and contrast-stretched.
**The DFC2019 contest terms restrict redistribution of this data. It is published here temporarily
by the repository owner and will be removed; do not reuse or redistribute it.**
Only the 42 tiles the Depth Wizard desktop app downloads on demand are here (no thumbnails).
