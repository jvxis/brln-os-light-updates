# LightningOS release catalog

This repository hosts immutable LightningOS releases **after 0.5.40**.

Development, pull requests, issues, and installation documentation remain in
[jvxis/brln-os-light](https://github.com/jvxis/brln-os-light).

## Mandatory upgrade bridge

- LightningOS versions below 0.5.40 use the original repository's release list.
  The last release published there must be **0.5.40**.
- Starting with 0.5.40, LightningOS checks this catalog for newer versions.
- Users continue updating through the LightningOS panel. Existing installations
  do not need to rerun the first-install scripts.

Release tags in this repository must mirror the exact reviewed source commits
from the development repository. This is a release mirror, not a separately
maintained codebase. Release immutability must remain enabled.

Use `scripts/prepare-release-draft.py` in the development checkout to derive
the correct destination and prepare a draft. Review and validate the final
integrated version before publication. Never publish 0.5.41 or later as a
release in the original repository.

The catalog is being prepared for the 0.5.40 bridge. Its creation does not
announce or publish a new LightningOS version.
