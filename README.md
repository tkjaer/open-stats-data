# open-stats-data

The published visit counts of [open-stats](https://github.com/tkjaer/open-stats):
one file per project and ISO week under `data/<project>/weekly/`, and the
GoatCounter settings observed at each export in
`data/<project>/goatcounter-settings.json`.

- **What the numbers mean, and what is and isn't collected:**
  [open-stats README](https://github.com/tkjaer/open-stats#readme).
- **File format:** [docs/data-format.md](https://github.com/tkjaer/open-stats/blob/main/docs/data-format.md).
- **Licence:** [CC0 1.0](LICENSE), no rights reserved.

Everything here is written by `open-stats export` on the server, which
pushes with a deploy key that can write to this repository only. No code
from here runs anywhere: GitHub Actions and Pages are switched off for this
repository, and the page at https://tkjaer.github.io/open-stats/ is built by
open-stats' own workflow, which checks every file strictly and treats it as
untrusted. Files are written once and kept, with their history,
indefinitely.
