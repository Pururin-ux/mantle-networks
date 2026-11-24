# Mantle Networks

Mantle public resources

### connect an application to mainnet

Use chain ID `5000` for Mantle Mainnet. The
[Chain.Love Mantle API directory](https://mantle.chain.love/toolbox/apis)
lists hosted RPC options and their advertised plan details. For historical state
queries, confirm archive access with the provider.

Set `MANTLE_RPC_URL` to your chosen HTTPS endpoint. Mantle Mainnet returns
`0x1388` for this check.

```sh
curl -sS -H 'Content-Type: application/json' \
  --data '{"jsonrpc":"2.0","id":1,"method":"eth_chainId","params":[]}' \
  "$MANTLE_RPC_URL"
```

### run a replica node
[run a node in mainnet](./run-node-mainnetv2.md)

[run a node in sepolia testnet](./run-node-sepolia.md)
