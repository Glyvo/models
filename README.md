# Glyvo models

Model files the [Glyvo](https://glyvo.app) dictation app downloads on demand. Each file is attached to a release with a
fixed tag; the app downloads it by that URL and checks its SHA-256 before use.

| Model | Release | Source | License |
|---|---|---|---|
| GigaAM-v3 e2e RNN-T (Russian speech recognition), Core ML | coming | GigaAM by the GigaChat Team (SaluteDevices), checkpoint `v3_e2e_rnnt` | MIT — see `LICENSE-GigaAM` |

The GigaAM files here are a conversion of the official checkpoint (sha256
`f60c62fe45902d967000770a12f260de7c5ac4d4b8e5e852f1df8c548e3958b5`) to Core ML; the weights are unchanged apart from
the format and fp16 storage.
