# py-libp2p — Akshit Agrawal's submissions

Fork of [seetadev/py-libp2p](https://github.com/seetadev/py-libp2p)

## Issue #22 — Decentralized Aggregation Strategies
PR: https://github.com/seetadev/py-libp2p/pull/52

Round-robin and gossip averaging for federated learning, no central
coordinator in either. Run it:
```bash
python examples/decentralized_aggregation/demo.py
pytest tests/core/federated/ -v
```

## Issue #32 — Filecoin-Compatible GossipSub Example
Branch: `feat/filecoin-gossipsub`

Reference example wiring two local peers over Filecoin's GossipSub
preset (real mesh params, Blake2b-256 message IDs, payload validation).
Run it:
```bash
python -m examples.filecoin.filecoin_gossipsub_example --network mainnet --topic both
pytest tests/core/filecoin/ -v
```
