# How to release a new version

Everything happens on GitHub. Zenodo is updated automatically.

1. Update `CHANGELOG.md` (and the version in `CITATION.cff`).
2. On GitHub: **Releases > Draft a new release**.
3. Tag: `vX.Y.Z` (e.g. `v1.0.1`). Title: `SoPhyFit-Evap X.Y.Z`. Paste the changelog entry as notes.
4. Drag `SoPhyFit-Evap_Setup_X.Y.Z.exe` into the release form and wait until the upload is finished.
5. Leave "Set as a pre-release" unticked. Click **Publish release**.

Within about a minute, a new Zenodo version (installer + documentation) is published under the same
"all versions" DOI, and its DOI is added to the release notes.

**If you forgot the installer:** nothing is sent to Zenodo and the run shows an error.
Attach the .exe to the release (Edit release), then go to
**Actions > Zenodo DOI on release > Run workflow**, enter the tag, and click **Run workflow**.
