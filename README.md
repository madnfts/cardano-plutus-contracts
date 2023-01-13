# MADNFTs Plutus Smart Contracts 1.x

---
### Overview
This repo contains the MADNFTs Plutus smart contracts. The following stack is used for development:
- nix
- cabal
- haskell
- plutus 

---
### Development

#### Clone plutus-apps repo
```
git clone https://github.com/input-output-hk/plutus-apps.git
git checkout 41149926c108c71831cfe8d244c83b0ee4bf5c8a
cd plutus-apps
```

Run the nix shell abnd setup local environemt
```
nix-shell
cd /madnfts-plutus-contracts
caba repl
```

#### Then load the Market.Trace module
```
:l Market.Trace
```

### Testing

After the above you can run the tests:
```
test
```