# Cardano

## Staking

- **No lock-up/waiting period:** Unstaking (i.e., stop delegating) occurs at any time, and the ADA is never locked.
  <br/>It always remains in the wallet and under wallet control (able to spend/sent).
- **Reward timing:** What does have a delay is the reward cycle. Cardano uses "epochs" (5-day periods).
  <br/>When first delegated, rewards only begin to accrue after about 15–20 days (three epochs)
  <br/>Similarly, when staking is stopped or switched pools, the change takes effect after the next epoch boundary and any rewards already earned from previous epochs.

**Suppose today is Day 1 of Epoch 500 (epochs are 5 days long):**
- Day 1 (Epoch 500) – Decide to stop staking (undelegate) or move ADA to another pool.
  - The ADA is immediately free — can send, swap, or spend it.
  - Delegation change is recorded but doesn’t take effect yet.
- Day 6 (Epoch 501 begins) – Change is registered on-chain, but rewards are still calculated based on delegation from Epoch 500.
- Day 11 (Epoch 502 begins) – New status (unstaked or new pool) is now used for block production and rewards.
- Day 16 (Epoch 503 begins) – Rewards from final staked epoch (Epoch 500) are paid out. After this, no new rewards accumulate if all tokens are fully unstaked.
