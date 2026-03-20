# Contract Architecture

The system is implemented through modular smart contracts, including the token contract, staking vaults, capital formation module, liquidity management logic, and balance sheet custody system.

Contracts are upgradeable while preserving system state. Infrastructure integrates with external networks for execution and indexing.

{% hint style="info" %}
**Architectural principle**

Contract modularity preserves state continuity while allowing controlled evolution of logic.
{% endhint %}

The architectural control layer is connected to [Governance System](../governance/README.md), while operational security is detailed in [Security Architecture](../system-controls/security-architecture.md).
