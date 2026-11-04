# Stackline changelog

## 1.0.5 - 2026-11-04

- Make npm select the Stackline README by giving upstream documentation a distinct filename.
- Check the README selected by the actual npm publication parser before release.

## 1.0.4 - 2026-11-04

- Publish the Stackline README with the correct package version.
- Preserve the original upstream README separately; runtime files remain unchanged.
- Verify the README inside the exact npm artifact before publication.

## 1.0.3 — 2026-11-04

- Publish updated development dependencies with security fixes.
- Validate and publish using patched supported Node.js releases.
- Preserve the reviewed upstream runtime payload while correcting development metadata.

## 1.0.0

- Adopt maintenance from `pg-copy-streams@7.0.0` with preserved source history and license.
- Maintenance adoption with preserved runtime payload. No runtime defect correction is claimed. Reports remain visible for subsequent targeted reproduction.
- Add tested, reproducible artifact publication with npm provenance and immutable release evidence.
