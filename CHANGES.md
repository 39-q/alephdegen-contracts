# Changes from alephium-dex

Forked from https://github.com/alephium/alephium-dex (LGPL 3.0).

## Modified contracts

The core DEX contracts in `dex/` (constants.ral, fee_collector_factory.ral, fee_collector_per_token_pair.ral, math.ral, router.ral, token_pair.ral, token_pair_factory.ral) show no line-level content changes from the original. Differences detected by hash comparison are limited to whitespace and/or line endings. The Swap and Pool contracts are used as-is.

Support files in `examples/`, `scripts/`, and `test/` likewise show no line-level content changes.

## Added contracts

- `Token.ral` — token contract
- `TokenFactory.ral` — token factory contract
- `dex/SwapExactTokenForToken.ral` — swap contract for token-to-token swaps

## Frontend / backend (not part of this repository)

The Alephdegen frontend and backend are separate from these contracts and are not covered by the LGPL obligations for the forked library.

## Source

Modified contract source: https://github.com/39-q/alephdegen-contracts

Date: 2026-11-07
