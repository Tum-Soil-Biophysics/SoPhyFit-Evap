# Changelog

All notable changes to SoPhyFit-Evap are listed here. Versions follow MAJOR.MINOR.PATCH:
PATCH = bug fixes, MINOR = new features, MAJOR = changes that can alter results or
make older project files incompatible. Each entry states whether results can differ
from the previous version.

## [1.0.0] - 2026-10-24

First public release.

- Reads HYPROP-FIT exports (retention, conductivity, WP4 points, fitted parameters) or any workbook with a retention and a conductivity sheet.
- Six models for retention and conductivity: van Genuchten-Mualem, Brooks-Corey, Kosugi, bimodal van Genuchten, PDI van Genuchten, PDI bimodal (film flow fitted).
- Simultaneous fit with error-based weights, or sequential fit; fit of each replicate and of all replicates of a treatment pooled.
- Fixed parameters set per treatment, with defaults from the HYPROP-FIT sheet of the files.
- 95% confidence intervals (delta method, Student t) for parameters, curves, field capacity (four methods), wilting point, plant-available water, user points and pore classes.
- Pore-size distribution and KA5 or user-defined pore classes.
- Units for display and output: h in cm, hPa or kPa; θ in cm³/cm³ or %; six K units.
- User guide (Help → User Guide); Cite Us tab with the citation and the DOI of the installed version; update check at start and in Help → Check for Updates.
