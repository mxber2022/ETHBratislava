# ETHBratislava

## Scaling Ethereum 1 - Deployed Rollups

**RollupName:** EBratislava  
**FrameWork:** Opstack  
**Settlement layer:** Ethereum L1  
**Data availability:** EigenDA  

EigenDA features:

- Lowers data availability cost and transaction fees  
- Eigen layer economic security  
- 100x higher throughput  
- 100x cheaper gas fees  

EigenDA is an innovative solution designed to store rollup transactions until their computed state is finalized on the rollup bridge. It distinguishes itself through several core features:

1. **Scalability:** EigenDA boasts exceptional scalability, with its write throughput scaling linearly with the number of operators. At launch, it will deliver a remarkable 10 MB/s of write throughput, surpassing competitors by a factor of 5.

2. **Security:** Security is a top priority for EigenDA, as it operates on a decentralized network composed of hundreds of registered operators within EigenLayer. These operators' delegated stake imposes an economic cost to misbehavior, ensuring the system's integrity. EigenDA will be backed by billions of dollars of economic security upon launch.

3. **Decentralization:** Inspired by Danksharding, EigenDA's design aims to surpass the limitations of Ethereum-native decentralized applications (DA) outlined in EIP-4844. It achieves decentralization by registering blob writes with contracts on Ethereum, subjecting operators to slashing risks. This approach eliminates the need for trust assumptions on other chains' light clients, which can be vulnerable to manipulation by dishonest validator sets.

In essence, EigenDA represents a groundbreaking advancement in the storage of rollup transactions, offering unparalleled scalability, security, and decentralization.

## Scaling Ethereum 2 - L3 orbit chain

- **Chain Id:** 59463755459  
- **Chain Name:** Bratislava  
- **Challenge Period Blocks:** #150  
- **Gas Token:** ETH  
- **Batch Poster Address:** 0x7f5814E1ebcAbB3BB38cA4c9eBe3EeC83321d0ca  
- **Validator:** 0x9c91EDae3Be3EA69D8A1439929b5cdb6dF7EbB34  

# Contract Addresses and Configuration

Below are the contract addresses and configuration details for the Bratislava chain:

- **Network Fee Receiver**: `0x7199D548f1B30EA083Fe668202fd5E621241CC89`
- **Infrastructure Fee Collector**: `0x7199D548f1B30EA083Fe668202fd5E621241CC89`
- **Rollup Contract**: `0x26C156B2b44bc54c6ef7D7eA303Fbb6477F15602`
- **Staker**: `0x9c91EDae3Be3EA69D8A1439929b5cdb6dF7EbB34`
- **Batch Poster**: `0x7f5814E1ebcAbB3BB38cA4c9eBe3EeC83321d0ca`
- **Inbox Contract**: `0x0386F7Ddce84673420dFe60d0C39f5B579485918`
- **Outbox Contract**: `0xcaf7ee49F0c13f1f7B8145Cbf324A6AF6A50a646`
- **Admin Proxy**: `0xC4e6ca39339ddAe478C394C6194b914ed57432EF`
- **Sequencer Inbox**: `0x7034709db79e9fD2c8C0F080D73Aa4fd5c6daf0b`
- **Bridge Contract**: `0xbeF0785bA2DCfe4E9B77b07eA0C0e234b6f80C1F`
- **Utilities Contract**: `0xB11EB62DD2B352886A4530A9106fE427844D515f`
- **Validator Wallet Creator**: `0xEb9885B6c0e117D339F47585cC06a2765AaE2E0b`
- **Deployed At Block Number**: `42802860`
- **Chain Owner**: `0x7199D548f1B30EA083Fe668202fd5E621241CC89`
- **Chain ID**: `59463755459`
- **Chain Name**: `Bratislava`
- **Minimum L2 Base Fee**: `100000000`
- **Parent Chain ID**: `421614`
- **Parent Chain Node URL**: [https://sepolia-rollup.arbitrum.io/rpc](https://sepolia-rollup.arbitrum.io/rpc)
- **Native Token**: `0x0000000000000000000000000000000000000000`
- **Rollup Event Inbox**: `0xF429C8755408f0E68dD589c7c3D5B9F6E4Bb3d82`
- **Challenge Manager**: `0xAA30b63EA5F04Cd908cE6006dD0aD047A4e690B7`
- **Upgrade Executor**: `0xCE659B798622B5BDa60572040375D8ec676C6Db6`
- **Validator Utilities**: `0xB11EB62DD2B352886A4530A9106fE427844D515f`

# Rollup Contracts

Below are the addresses of various contracts related to the Rollup system:

- **Rollup Address**: `0x26C156B2b44bc54c6ef7D7eA303Fbb6477F15602`
- **Inbox Address**: `0x0386F7Ddce84673420dFe60d0C39f5B579485918`
- **Outbox Address**: `0xcaf7ee49F0c13f1f7B8145Cbf324A6AF6A50a646`
- **Admin Proxy Address**: `0xC4e6ca39339ddAe478C394C6194b914ed57432EF`
- **Sequencer Inbox Address**: `0x7034709db79e9fD2c8C0F080D73Aa4fd5c6daf0b`
- **Bridge Address**: `0xbeF0785bA2DCfe4E9B77b07eA0C0e234b6f80C1F`
- **Validator Utils Address**: `0xB11EB62DD2B352886A4530A9106fE427844D515f`
- **Validator Wallet Creator Address**: `0xEb9885B6c0e117D339F47585cC06a2765AaE2E0b`
- **Upgrade Executor Address**: `0xCE659B798622B5BDa60572040375D8ec676C6Db6`
- **Deployed At Block Number**: `42802860`


Rollup Config

{
  "chain": {
    "info-json": "[{\"chain-id\":59463755459,\"parent-chain-id\":421614,\"parent-chain-is-arbitrum\":true,\"chain-name\":\"Bratislava\",\"chain-config\":{\"homesteadBlock\":0,\"daoForkBlock\":null,\"daoForkSupport\":true,\"eip150Block\":0,\"eip150Hash\":\"0x0000000000000000000000000000000000000000000000000000000000000000\",\"eip155Block\":0,\"eip158Block\":0,\"byzantiumBlock\":0,\"constantinopleBlock\":0,\"petersburgBlock\":0,\"istanbulBlock\":0,\"muirGlacierBlock\":0,\"berlinBlock\":0,\"londonBlock\":0,\"clique\":{\"period\":0,\"epoch\":0},\"arbitrum\":{\"EnableArbOS\":true,\"AllowDebugPrecompiles\":false,\"DataAvailabilityCommittee\":true,\"InitialArbOSVersion\":11,\"GenesisBlockNum\":0,\"MaxCodeSize\":24576,\"MaxInitCodeSize\":49152,\"InitialChainOwner\":\"0x7199D548f1B30EA083Fe668202fd5E621241CC89\"},\"chainId\":59463755459},\"rollup\":{\"bridge\":\"0xbeF0785bA2DCfe4E9B77b07eA0C0e234b6f80C1F\",\"inbox\":\"0x0386F7Ddce84673420dFe60d0C39f5B579485918\",\"sequencer-inbox\":\"0x7034709db79e9fD2c8C0F080D73Aa4fd5c6daf0b\",\"rollup\":\"0x26C156B2b44bc54c6ef7D7eA303Fbb6477F15602\",\"validator-utils\":\"0xB11EB62DD2B352886A4530A9106fE427844D515f\",\"validator-wallet-creator\":\"0xEb9885B6c0e117D339F47585cC06a2765AaE2E0b\",\"deployed-at\":42802860}}]",
    "name": "Bratislava"
  },
  "parent-chain": {
    "connection": {
      "url": "https://sepolia-rollup.arbitrum.io/rpc"
    }
  },
  "http": {
    "addr": "0.0.0.0",
    "port": 8449,
    "vhosts": [
      "*"
    ],
    "corsdomain": [
      "*"
    ],
    "api": [
      "eth",
      "net",
      "web3",
      "arb",
      "debug"
    ]
  },
  "node": {
    "sequencer": true,
    "delayed-sequencer": {
      "enable": true,
      "use-merge-finality": false,
      "finalize-distance": 1
    },
    "batch-poster": {
      "max-size": 90000,
      "enable": true,
      "parent-chain-wallet": {
        "private-key": "24cf947e1b62afcff90ef8d7522463058b232407c5f438381aba8c6a64d1fd1d"
      }
    },
    "staker": {
      "enable": true,
      "strategy": "MakeNodes",
      "parent-chain-wallet": {
        "private-key": "e05cecbf2fdd760e119a8a6dac5ddca8d26b04aa4276c793ceb0b6559af94045"
      }
    },
    "dangerous": {
      "no-sequencer-coordinator": true
    },
    "data-availability": {
      "enable": true,
      "sequencer-inbox-address": "0x7034709db79e9fD2c8C0F080D73Aa4fd5c6daf0b",
      "parent-chain-node-url": "https://sepolia-rollup.arbitrum.io/rpc",
      "rest-aggregator": {
        "enable": true,
        "urls": [
          "http://localhost:9877"
        ]
      },
      "rpc-aggregator": {
        "enable": true,
        "assumed-honest": 1,
        "backends": "[{\"url\":\"http://localhost:9876\",\"pubkey\":\"YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA==\",\"signermask\":1}]"
      }
    }
  },
  "execution": {
    "forwarding-target": "",
    "sequencer": {
      "enable": true,
      "max-tx-data-size": 85000,
      "max-block-speed": "250ms"
    },
    "caching": {
      "archive": true
    }
  }
}


keyset - A Keyset specifies the public keys of Committee members and the number of signatures required for a Data Availability Certificate to be valid. Keysets make Committee membership changes possible and provide Committee members the ability to change their keys.0x00000000000000010000000000000001012160000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
