# <img src="../icons/mechanisms.svg" width="24"/> LP Rewards

To distribute liquidity incentives efficiently, Maxum uses a dividend-per-share style reward model. Instead of looping through all participants, the system updates a global accumulator whenever distributable fees are collected.

This allows liquidity providers to claim rewards on demand while keeping gas costs manageable. It also ensures that fee-based rewards scale alongside market activity.

LP rewards matter because they keep liquidity attractive while still preserving the protocol’s broader emphasis on retained, system-strengthening market depth.

<img src="../diagrams/lp-rewards.svg" alt="LP Rewards" width="1200"/>

> [!NOTE]
> Efficient accounting makes fee distribution scalable without turning rewards into a gas burden.
