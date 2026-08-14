---
'@solana/kit-plugin-instruction-plan': minor
'@solana/kit-plugin-litesvm': minor
'@solana/kit-plugin-rpc': minor
'@solana/kit-plugin-signer': minor
'@solana/kit-plugin-wallet': minor
---

Update Kit dependency to v7.1.0.

The `rpcTransactionPlanSendingExecutor` and `litesvmTransactionPlanSendingExecutor` executors now report the result context directly instead of returning a transaction, which Kit deprecated in v7.1.0. Successful results carry the same `signature` and `transaction` as before, so no changes are required.
