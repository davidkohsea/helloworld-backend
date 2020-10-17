



# node index.js --help
Usage: index [options]

Options:
  -d, --debug                  output debug info
  -l, --latest-block           latest block info
  -b, --block                  output block info
  -s, --block-hash <hash>      block hash
  -n, --block-height <number>  block height
  -w, --ws-url <wsurl>         WsProvider URL
  -h, --help                   display help for command




 # node index.js -l -b  -w wss://kusama-rpc.polkadot.io
{
  "header": {
    "parentHash": "0x943e16d4a526e2f1f81fdd69bd714a8e289901f8993eb02e3aef44a02cdf5613",
    "number": 4515640,
    "stateRoot": "0x567ba98119e059a1c61c7ec1e7ac513777c79e246dab2691d558473ecd63f6a7",
    "extrinsicsRoot": "0x1d71575bbd66ba746add307356c8261ebce171b97c97b7d19a65fbeae1e93279",
    "digest": {
      "logs": [
        {
          "PreRuntime": [
            1161969986,
            "0x02550100006681ec0f00000000"
          ]
        },
        {
          "Seal": [
            1161969986,
            "0x30d6ce3bb0fbe1dd264f818e734f42b3c3c06cee2345210e4aba90b6513f6841c100376e596a86f47bad2d15da9efea98f65df8d872d9c27090467083cc2ad80"
          ]
        }
      ]
    }
  },
  "extrinsics": [
    "0x280402000ba0c618377501"
  ]
}


