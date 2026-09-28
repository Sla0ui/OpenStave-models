# OpenStave models

The recognition models of the OpenStave app. They run entirely on the device; no scan ever leaves the phone.

Each release holds one model set as zip files. The app's build fetches them from here, checks every file against the SHA-256 checksums pinned in the app, and ships them inside the app, so the app itself never downloads anything. `SHA256SUMS` lists the checksums of the zips.

| Release | Files |
|---|---|
| `set-426` | `segnet_308` (page segmentation), `encoder` and `decoder` run 426 (staff transcription), ONNX |

Distributed for use with the OpenStave app.

## Verovio source

The app engraves scores with Verovio (LGPL-3.0), built with one change. [`verovio/`](verovio) holds that change,
the build script and how to rebuild it; the `verovio-6.3.0` release holds the full source archive.

## Privacy policy

The app's privacy policy is served from [`privacy/`](privacy) at https://sla0ui.github.io/OpenStave-models/privacy/.
