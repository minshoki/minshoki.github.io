# Today's Camp sky catalog — data attribution and distribution notice

`CampStarCatalog.json` is an adapted data collection distributed under **Creative Commons Attribution-ShareAlike 4.0 International**:
https://creativecommons.org/licenses/by-sa/4.0/
The full legal text is included as `CC-BY-SA-4.0.txt`.

## Source credits

- **HYG Stellar Database v4.1 — Astronomy Nexus / astronexus**, CC BY-SA 4.0. Project: https://www.astronexus.com/projects/hyg . Exact archived input: https://github.com/astronexus/HYG-Database/blob/c7f7f883fe678cc7680169a50ccd7dcc49b060ce/hyg/CURRENT/hygdata_v41.csv . The version-specific license is in the same revision's `LICENSE` and `hyg/README.md`.
- **Modern sky culture constellation line data — Stellarium's team**, CC BY-SA 4.0. Exact source: https://github.com/Stellarium/stellarium/blob/ffa6794fd0aedb9afb5a49095b75095b43f7fb80/skycultures/modern/index.json . Authorship and data license: the same revision's `skycultures/modern/description.md`, Authors and License sections. No Stellarium illustrations or application code are included.

## Changes made for Today's Camp

Filtered HYG to apparent visual magnitude <=5.6, excluding the Sun, and included four fainter stars required to preserve selected constellation lines. Converted right ascension from hours to degrees; rounded coordinates to six decimal places; selected visual magnitude and B−V colour index (unknown colour defaults to neutral 0.65). Sorted by magnitude then stable HYG ID. Converted 46 selected Stellarium constellation polylines to indexed segments and deduplicated undirected edges. Added Korean/international names and spherical label centroids. Selected and translated 27 common star names. Reformatted as Unity-compatible JSON. The resulting data adaptations are also CC BY-SA 4.0. No source author endorses Today's Camp.

## Release integration requirements

1. Include this notice and the complete license with distributed catalog data. Show an accessible in-game credits entry identifying HYG/Astronomy Nexus, Stellarium's team, the license, source links and modifications.
2. Keep the catalog and this notice identifiable as separately licensed data. Do not attach a game-wide proprietary restriction to recipients' rights in these data.
3. Distribute the adapted data under the same license without additional legal or effective technological restrictions. The prepared `CampSkyData-CC-BY-SA-4.0.zip` is an unrestricted data package suitable for inclusion with release downloads. Providing a publicly accessible copy alongside store distribution is the intended release workflow; no upload/publication has been performed here.
4. These notes record the source authors' published license terms and the planned data separation; they are not a determination about every applicable distribution platform or the legal status of unrelated game code. Review the actual release packaging against those terms.

`reference-positions.json` is validation-only and is not included in the runtime data package. Its coordinate cross-checks were queried from CDS Sesame/SIMBAD (https://simbad.cds.unistra.fr/). Credit: This work made use of the SIMBAD database, operated at CDS, Strasbourg, France.

Source versions and SHA-256 values are recorded in `sources.lock.json`. Licenses verified from primary sources on 2026-11-13. HYG v4.1 is deliberately pinned for reproducibility; it is not claimed to be the latest HYG release.
