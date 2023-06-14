# ZkEra-Zro
Builder of Bridge
ZkSync, make access L0 messages:
Example
 //hardhat.config.ts

ethereum: {

    url: `{rpc address}`,

    chainId: 1, //chainlist id

}

//endpoints.json

"production": {

   ...

   "ethereum": {

     "id": 1 //layerzero chain id

   }

}
