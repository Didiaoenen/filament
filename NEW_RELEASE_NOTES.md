# Filament Release Notes log

**If you are merging a PR into main**: please add the release note below, under the *Release notes
for next branch cut* header.

**If you are cherry-picking a commit into an rc/ branch**: add the release note under the
appropriate header in [RELEASE_NOTES.md](./RELEASE_NOTES.md).

## Release notes for next branch cut
- materials: remove dependence on per-view descset layout from filamat. [⚠️ **New Material Version**]
- `ColorGrading::Builder::toneMapper` now takes a `shared_ptr<ToneMapper>`
