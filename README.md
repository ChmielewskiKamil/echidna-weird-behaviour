### Steps to reproduce the issue:
1. Clone the repo `git clone https://github.com/ChmielewskiKamil/echidna-weird-behaviour.git`
2. `cd echidna-weird-behaviour`
3. Install submodules with `forge install`
4. Run Echidna `echidna-test src/WeirdLogs.sol --contract WeirdLogs --config echidna_config.yaml`
5. Compare with Foundry results `forge test -vvv`