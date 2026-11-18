[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on007719-blue)](https://doi.org/10.82901/nemar.on007719)

<!-- nemar:provenance -->
## Provenance

This dataset is mirrored on NEMAR from OpenNeuro.

- Source: [ds007719](https://openneuro.org/datasets/ds007719)
- DOI: [10.18112/openneuro.ds007719.v1.0.0](https://doi.org/10.18112/openneuro.ds007719.v1.0.0)

## Data notes

- trial_type in the `*_events.tsv` files uses single-letter codes (G, H, J, L, Z); the `*_events.json` files hold
  only the template description of trial_type, so the meaning of the codes is not stated in this dataset (source:
  the events.tsv and events.json files of this dataset).
- 34 of the 65 `*_events.tsv` files are not sorted by onset (BIDS validator warning EVENT_ONSET_ORDER; counted in
  the events.tsv files of this dataset).
