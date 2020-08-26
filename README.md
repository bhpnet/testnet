# Join BHP Testnet
1. Install `bhpd` and `bhpcli`. Reference to [BHP repo](https://github.com/bhpnet/bhp)
2. Execute command `bhpd init <moniker> --chain-id=testing`  (`<moniker>` is your node name.)
3. Edit `~/.bhpd/config/config.toml` at line 171.Set
`persistent_peers = "34c3a69b0edad15d1de19abc15390cde3df792bd@101.133.225.179:26656,35d9bf1cedb4963469507d81e71acfcf202aa898@101.133.151.154:26656,bdc14bc6e14a97ee6f56fb3b17c3a9bd09fc4c73@47.103.97.77:26656"`
4. Download `genesis.json` in this repo and replace the default `~/.bhpd/config/genesis.json`
5. Execute command `bhpd start`
6. Please refer to [join-bhp-testnet.html](https://docs.bhpnet.io/getting-start/join-bhp-testnet.html) if you want to be a validator.
