# V3.1 MainNet Release Notes 

## [v0.8.9 - 19/1/2024](https://github.com/reapchain/reapchain/releases/tag/v0.8.9)

## Changes
- **Reapchain Core Upgrade:** In this release, we have upgraded Reapchain Core to `v0.34.20-reap.core.v0.1.24` [View Changes](https://github.com/reapchain/reapchain-core/releases/tag/v0.34.20-reap.core.v0.1.24) 
- **IAVL Upgrade:** In this release, we have upgraded IAVL to `v0.19.0-reap.iavl.v0.2.15` [View Changes](https://github.com/reapchain/iavl/releases/tag/v0.19.0-reap.iavl.v0.2.15) 
- **Cosmos-SDK Upgrade:** In this release, we have upgraded Cosmos-SDK to `v0.45.7-reap.sdk.v0.4.19` [View Changes](https://github.com/reapchain/cosmos-sdk/releases/tag/v0.45.7-reap.sdk.v0.4.19) 
- **IBC-GO Upgrade:** In this release, we have upgraded IBC-GO to `v3.2.0-reap.ibc.v0.5.20` [View Changes](https://github.com/reapchain/ibc-go/releases/tag/v3.2.0-reap.ibc.v0.5.20) 
- **Ethermint Upgrade:** In this release, we have upgraded Ethermint to `v0.19.0-reap.ethermint.v0.2.19` [View Changes](https://github.com/reapchain/ethermint/releases/edit/v0.19.0-reap.ethermint.v0.2.19) 


# Changelog

# v0.8.9-rc5.2 - 27/12/2023

## Changes
Due to ongoing issues downgraded to a stable version of Reapchain Core.

- **Cosmo-SDK:** Downgraded Cosmos-SDK to `v0.45.7-reap.sdk.v0.4.17`  
- **IBC-GO:** Downgraded IBC-GO to `v3.2.0-reap.ibc.v0.5.18`  
- **Ethermint:** Downgraded IBC-GO to `v0.19.0-reap.ethermint.v0.2.17`  
- **Reapchain Core:** Downgraded Reapchain Core to `v0.34.20-reap.core.v0.1.21`  
- **IAVL:** Downgraded IAVL to `v0.19.0-reap.iavl.v0.2.12`  

# v0.8.9-rc5.1 - 20/12/2023

## Improvements
- **features/bridge-genesis-invariants** Branch `[features/bridge-genesis-invariants]` merged.

  - **LastObservedEthereumBlockHeight:** Modified invariants check.
  [View Changes](https://github.com/reapchain/reapchain/tree/features/bridge-genesis-invariants)

## Bug Fixes
- **bug/bridge-export** Branch `[bug/bridge-export]` merged.

  - **Export Bug Fix:** Fixed missing defaultErc20ContractAddress’s values when running 'export'.
  [View Changes](https://github.com/reapchain/reapchain/tree/bug/bridge-export)

- **feature/permissions-module** Branch `[feature/permissions-module]` merged.

  - **Empty Validator Bug Fix:** Fixed bug when getting a validator returns a 'nil' value.
  [View Changes](https://github.com/reapchain/reapchain/tree/feature/permissions-module)


# v0.8.9-rc5 - 30/11/2023

## Improvements
- **feature/refactor-test-code** Branch `[feature/refactor-test-code]` merged.

  - **Test Code Refactor:** Updated imports used in test codes. Cleaned up go.mod.

  [View Changes](https://github.com/reapchain/reapchain/tree/feature/refactor-test-code)

## Changes
- **Reapchain Core Upgrade:** In this release, we have upgraded Reapchain Core to `v0.34.20-reap.core.v0.1.23` [View Changes](https://github.com/reapchain/reapchain-core/releases/tag/v0.34.20-reap.core.v0.1.23) 
- **IAVL Upgrade:** In this release, we have upgraded IAVL to `v0.19.0-reap.iavl.v0.2.14` [View Changes](https://github.com/reapchain/iavl/releases/tag/v0.19.0-reap.iavl.v0.2.14) 
- **Cosmos-SDK Upgrade:** In this release, we have upgraded Cosmos-SDK to `v0.45.7-reap.sdk.v0.4.18` [View Changes](https://github.com/reapchain/cosmos-sdk/releases/tag/v0.45.7-reap.sdk.v0.4.18) 
- **IBC-GO Upgrade:** In this release, we have upgraded IBC-GO to `v3.2.0-reap.ibc.v0.5.19` [View Changes](https://github.com/reapchain/ibc-go/releases/tag/v3.2.0-reap.ibc.v0.5.19) 
- **Ethermint Upgrade:** In this release, we have upgraded IBC-GO to `v0.19.0-reap.ethermint.v0.2.18`  [View Changes](https://github.com/reapchain/ethermint/releases/tag/v0.19.0-reap.ethermint.v0.2.18) 


# v0.8.9-rc4.1 - 28/11/2023

## Improvements
- **features/refactoring-for-reapchain** Branch `[features/refactoring-for-reapchain]` merged.

  - **Keyword Change:** `evmos -> reapchain` 
  - **Upgrade Legacy Code Removed** 
  - **Test Code Modifications:** 
  - **General Refactoring** 

  [View Changes](https://github.com/reapchain/reapchain/compare/features/refactoring-for-reapchain)

- **feature/escrow_module** Branch `[feature/escrow_module]` merged.

  - **Updated Governance Proposals:** Optional `reciever` for Escrow Conversions 
  - **Improved Flow:** Removed unexecuted code 
  - **General Refactoring** 

  [View Changes](https://github.com/reapchain/reapchain/tree/feature/escrow_module)

## Bug Fixes
- **bug/bridge-slashing** Branch `[bug/bridge-slashing]` merged.

  - **Slashing process limited to only target Standing Members** 
  
  [View Changes](https://github.com/reapchain/reapchain/tree/bug/bridge-slashing)

---
## Changes
- **Cosmo-SDK Upgrade:** In this release, we have upgraded Cosmos-SDK to `v0.45.7-reap.sdk.v0.4.17`  
- **IBC-GO Upgrade:** In this release, we have upgraded IBC-GO to `v3.2.0-reap.ibc.v0.5.18`  
- **Ethermint Upgrade:** In this release, we have upgraded IBC-GO to `v0.19.0-reap.ethermint.v0.2.17`  
- **Reapchain Core Downgrade:** In this release, we have downgraded Reapchain Core to `v0.34.20-reap.core.v0.1.21`  
- **IAVL Downgrade:** In this release, we have downgraded IAVL to `v0.19.0-reap.iavl.v0.2.12`  
 

# [v0.8.9-rc4] - 2023-11-13

## Improvements
* (features/Modify-SetOrchestratorAddress) - In the case of a steering member, address validation checks are not performed.
* Bump Cosmos-SDK version from v0.45.7-reap.sdk.v0.4.15 to v0.45.7-reap.sdk.v0.4.16
* Bump IBC-GO version from v3.2.0-reap.ibc.v0.5.16 to v3.2.0-reap.ibc.v0.5.17
* Bump Ethermint version from v0.19.0-reap.ethermint.v0.2.15 to v0.19.0-reap.ethermint.v0.2.16
