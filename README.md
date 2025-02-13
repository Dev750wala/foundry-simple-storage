#### compile the contracts:
- ```forge compile```

#### to start a local network of blockchain:
- ```anvil```

#### deploy Smart Contract using forge using CLI
- ```forge create SimpleStorage --interactive```

#### deploy Smart Contract using forge using script
- ```forge script scritp/SimpleStorage.s.sol --rpc-url http://lcoaljfo.com```

#### convert HEX to decimal:
- ```cast --to-base HEX_VALUE dec```

#### To keep the private key secure, don't use .env file.
- ```cast wallet import KEY_NAME --interactive```
  - KEY_NAME: name your key, whichever you want to
  
- ```cast wallet list``` - to list down all the keys

### Zk-Sync Foundry:
- install the L2 ethereum Zk-Sync: 
  - ```curl -L https://raw.githubusercontent.com/matter-labs/foundry-zksync/main/install-foundry-zksync | bash ```

- run the file installed by this command. ```./foundryup-zksync```
- to revert back to vanilla foundry: ```foundryup```
  - This is how to switch between these two.

#### To build with the zk-sync:
```forge build --zksync```