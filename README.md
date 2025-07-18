
# Silent Fingerprint Bypass PoC

## Description
This PoC demonstrates a potential vulnerability in entropy-based fingerprinting systems that do not account for silent deviation attacks where manipulated input replicates the original entropy pattern.

## Structure
- `src/utils/entropy.sol` — fingerprint utility logic.
- `test/PoC.t.sol` — test proving fingerprint reproducibility using identical entropy.
- `foundry.toml` — minimal config to run the PoC using Foundry.

## How to Run
1. Install Foundry: https://book.getfoundry.sh/getting-started/installation
2. Run the test: `forge test --match-test testBypassFingerprint`
