# INSPIRED BY THE POLKADOT-FRONTIER PROJECT AND TAKES ALL FILES AND CODE FROM THE POLKADOT ECOSYSTEM
## Kahawa Frontier

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/MJR-Mu7/frontier/test.yml)](https://github.com/MJR-Mu7/frontier/actions)
[![Matrix](https://img.shields.io/matrix/frontier:matrix.org)](https://matrix.to/#/#frontier:matrix.org)

Frontier is the EVM backbone of Kahawa and Kobole blockchains.

## Features
This version features a custom client RPC that handles BabeConsensusDataProvider allowing NPoS and PoS chains to add EVM via Frontier to their ecosystem.

Frontier is also a migration framework.
Besides the common strategy of direct state export/import and transaction-level replays, Frontier's Pre-Log Wrapper Block feature provides a possible method for a zero-downtime live migration.
