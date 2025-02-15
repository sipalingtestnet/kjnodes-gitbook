# Services

<figure><img src="https://raw.githubusercontent.com/kj89/testnet_manuals/main/pingpub/logos/rebus.png" width="150" alt=""><figcaption></figcaption></figure>

Rebuschain is a platform that will provide DeFi (Decentralized Finance)  investment opportunities to traditional investors clearly and conveniently

**Chain ID**: reb_1111-1 | **Latest Version Tag**: v0.3.0 | **Wasm**: OFF

[Website](https://www.rebuschain.com) | [Discord](https://discord.gg/rebuschain) | [Twitter](https://twitter.com/RebusChain)

[![Stake with kjnodes](https://i.ibb.co/cr44Q8j/button-stake-with-kjnodes.png)](https://restake.app/rebus/rebusvaloper1vndzy8y55ylgpmmsc34uy8rm6kqlml6ffs9lrv)

## Restake

[Restake with kjnodes](https://restake.app/rebus/rebusvaloper1vndzy8y55ylgpmmsc34uy8rm6kqlml6ffs9lrv) (every 5 minutes)
## Chain explorer
[https://explorer.kjnodes.com/rebus](https://explorer.kjnodes.com/rebus)

## Public endpoints

* api: [https://rebus.api.kjnodes.com](https://rebus.api.kjnodes.com)
* rpc: [https://rebus.rpc.kjnodes.com](https://rebus.rpc.kjnodes.com)
* grpc: [https://rebus.grpc.kjnodes.com](https://rebus.grpc.kjnodes.com)

## Peering

**state-sync**

```text
d9bfa29e0cf9c4ce0cc9c26d98e5d97228f93b0b@rebus.rpc.kjnodes.com:21656
```

**seed-node**

```text
400f3d9e30b69e78a7fb891f60d76fa3c73f0ecc@rebus.rpc.kjnodes.com:21659
```

**addrbook**
```bash
curl -Ls https://snapshots.kjnodes.com/rebus/addrbook.json > $HOME/.rebusd/config/addrbook.json
```

**live-peers** (30)
```bash
peers="256d9790bf186f5a275790f7fe01e1b8800dcaaf@65.21.88.78:26656,12e6bea6650a53150c01ca3897e4a0b94d6e9d4e@135.181.141.47:26656,d28516746773bfaeca4efa5537c0bf5990b8828e@65.21.229.33:27656,641b33b0e909630868133820605edf2b4ba4969a@65.109.49.109:26656,92245ff5c7a4b293d2f0c7f9afca0ddad2e0fb52@65.108.244.178:26656,87102b5dd22c1d17f97197c078f23726ae3c6214@91.157.60.253:26656,89757803f40da51678451735445ad40d5b15e059@169.155.44.106:26656,4e3e545e85000045ef44905ab683a5db6f87cdbe@88.198.32.17:37656,ff7621be29e39e9fdf07f2501e1a217201ca29ee@213.239.207.175:39656,8f023504e27873141164b6fbf1c4b788ff8d533b@159.69.200.24:26656,1fe32d8f09b8715b1e626da17b3ecfe26623b371@176.9.22.117:27656,69e27ab9b46350654805df3ea8d9ac2f00af4e4c@38.242.244.85:26656,ce38728ac38ebbb4a72d496d42f8e9030af441d7@162.19.137.25:26656,89ded0a3987d22e46b756fead439e2a4d25f23cb@185.144.99.30:26656,34e3178b6e0f25451fd690c15fc199d5a9bdfb9b@15.204.197.11:26656,ebc4d27be0c87f537b44250c2e22ad349dc59fb6@158.69.116.134:26656,07b84cf4b47a2e5ad251267716fe05bcf30330cd@65.21.170.3:29656,b1b08fe470551dca6d6631fb1bfabb814f6c1aec@54.37.129.164:54556,ae67d4c37632435e0d5f27041f50af20d227bdc2@93.170.72.118:21656,241c83e7a6ff769d66be0c4848db44cdcac8b4b0@192.99.62.83:26656,6dc49b312a98051351f0347568c294fea83a5f9a@51.79.27.21:11656,cd71aa366822800a2aa7051fae69127f78b3f203@188.165.225.226:26656,346bf012c17fa30ef70ae72f082374838626532a@65.108.106.131:26696,a3d975c913570ad217d9a3de01a8616ad5ce20f8@142.132.128.137:26656,e6f1684ed8ed5c586b188bf7088026da4ffdaff6@134.65.193.78:26656,c126eed9cfede7802d78f570fec8175835309a73@141.95.127.146:26656,faf349e185255c4aa2786da4f8ac70ea13849db0@169.155.45.128:26656,e056318da91e77585f496333040e00e12f6941d1@51.83.97.166:26656,d9bfa29e0cf9c4ce0cc9c26d98e5d97228f93b0b@65.109.88.38:21656,1fcb45323f9045707c0c344a60d7cb906008cfaf@65.109.80.176:26656"
sed -i -e "s|^persistent_peers *=.*|persistent_peers = \"$peers\"|" $HOME/.rebusd/config/config.toml
```
