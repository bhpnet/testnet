# Join BHP Testnet
1. Install `bhpd` and `bhpcli`. Reference to [BHP repo](https://github.com/bhpnet/bhp)
2. Execute command `bhpd init <moniker> --chain-id=testing`  (`<moniker>` is your node name.)
3. Edit `~/.bhpd/config/config.toml` at line 171.Set
`persistent_peers = "42ef29916a27051540fb500c6aa6e177266117ec@47.103.97.77:26656,b5917e54c869d753f44de349b672b10ce1bfa2b2@47.103.38.41:26656,cbec44e01d28f6de0b0daad57f974091fb670b7a@101.133.225.179:26656,7ce672f152baf0530a2b6f91cfe5b7c68c8bae4d@101.133.151.154:26656"`
4. Download `genesis.json` in this repo and replace the default `~/.bhpd/config/genesis.json`
5. Execute command `bhpd start`
6. Please refer to [join-bhp-testnet.html](https://docs.bhpnet.io/getting-start/join-bhp-testnet.html) if you want to be a validator.
