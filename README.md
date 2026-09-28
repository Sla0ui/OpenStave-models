# OpenStave models

The recognition models that the OpenStave app downloads on first use, after the user agrees. They run entirely on the device; no scan ever leaves the phone.

Each release holds one model set as zip files. The app checks every file against a SHA-256 checksum built into it and rejects anything else. `SHA256SUMS` lists the checksums of the zips.

| Release | Files |
|---|---|
| `set-426` | `segnet_308` (page segmentation), `encoder` and `decoder` run 426 (staff transcription), ONNX |

Distributed for use with the OpenStave app.
