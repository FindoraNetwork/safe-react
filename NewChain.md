## How to add a new chain.

- https://safe-config-service.multisig.findora.org/admin/chains/chain/add/
- `git clone https://github.com/FindoraNetwork/safe-react`
  `yarn instal`
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/compatibility_fallback_handler.json add CompatibilityFallbackHandler address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/create_call.json add CreateCall address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/gnosis_safe.json add GnosisSafe address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/gnosis_safe_l2.json add GnosisSafeL2 address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/multi_send.json add MultiSend address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/multi_send_call_only.json add MultiSendCallOnly address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/proxy_factory.json add GnosisSafeProxyFactory address
- node_modules/@gnosis.pm/safe-deployments/dist/assets/v1.3.0/sign_message_lib.json add SignMessageLib address
- `npx patch-package @gnosis.pm/safe-deployments`
- `git pull``
