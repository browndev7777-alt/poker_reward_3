# poker_reward_3

Stacked ensemble detector for Poker44 (Bittensor SN126).

Returns a per-chunk risk score in [0,1].
Model weights ship in `models/current.joblib`; see `model_manifest.json`.

## Data attestation
No validator-private evaluation labels are used for training. Training uses released benchmark data and local runtime features.
