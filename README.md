# ETHBratislava
 
Chain Id - 59463755459
Chain Name - Bratislava
Challenge Period Blocks #150
Gas Token - ETH
Batch Poster Address - 0x7f5814E1ebcAbB3BB38cA4c9eBe3EeC83321d0ca
Validator - 0x9c91EDae3Be3EA69D8A1439929b5cdb6dF7EbB34

keyset - A Keyset specifies the public keys of Committee members and the number of signatures required for a Data Availability Certificate to be valid. Keysets make Committee membership changes possible and provide Committee members the ability to change their keys.0x00000000000000010000000000000001012160000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000

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


L3 Config

{
  "networkFeeReceiver": "0x7199D548f1B30EA083Fe668202fd5E621241CC89",
  "infrastructureFeeCollector": "0x7199D548f1B30EA083Fe668202fd5E621241CC89",
  "rollup": "0x26C156B2b44bc54c6ef7D7eA303Fbb6477F15602",
  "staker": "0x9c91EDae3Be3EA69D8A1439929b5cdb6dF7EbB34",
  "batchPoster": "0x7f5814E1ebcAbB3BB38cA4c9eBe3EeC83321d0ca",
  "inbox": "0x0386F7Ddce84673420dFe60d0C39f5B579485918",
  "outbox": "0xcaf7ee49F0c13f1f7B8145Cbf324A6AF6A50a646",
  "adminProxy": "0xC4e6ca39339ddAe478C394C6194b914ed57432EF",
  "sequencerInbox": "0x7034709db79e9fD2c8C0F080D73Aa4fd5c6daf0b",
  "bridge": "0xbeF0785bA2DCfe4E9B77b07eA0C0e234b6f80C1F",
  "utils": "0xB11EB62DD2B352886A4530A9106fE427844D515f",
  "validatorWalletCreator": "0xEb9885B6c0e117D339F47585cC06a2765AaE2E0b",
  "deployedAtBlockNumber": 42802860,
  "chainOwner": "0x7199D548f1B30EA083Fe668202fd5E621241CC89",
  "chainId": 59463755459,
  "chainName": "Bratislava",
  "minL2BaseFee": 100000000,
  "parentChainId": 421614,
  "parent-chain-node-url": "https://sepolia-rollup.arbitrum.io/rpc",
  "nativeToken": "0x0000000000000000000000000000000000000000",
  "rollupEventInbox": "0xF429C8755408f0E68dD589c7c3D5B9F6E4Bb3d82",
  "challengeManager": "0xAA30b63EA5F04Cd908cE6006dD0aD047A4e690B7",
  "upgradeExecutor": "0xCE659B798622B5BDa60572040375D8ec676C6Db6",
  "validatorUtils": "0xB11EB62DD2B352886A4530A9106fE427844D515f"
}

Rollup Contracts

Rollup address:
0x26C156B2b44bc54c6ef7D7eA303Fbb6477F15602
Inbox address:
0x0386F7Ddce84673420dFe60d0C39f5B579485918
Outbox address:
0xcaf7ee49F0c13f1f7B8145Cbf324A6AF6A50a646
Admin Proxy address:
0xC4e6ca39339ddAe478C394C6194b914ed57432EF
Sequencer Inbox address:
0x7034709db79e9fD2c8C0F080D73Aa4fd5c6daf0b
Bridge address:
0xbeF0785bA2DCfe4E9B77b07eA0C0e234b6f80C1F
Validator Utils address:
0xB11EB62DD2B352886A4530A9106fE427844D515f
Validator Wallet Creator address:
0xEb9885B6c0e117D339F47585cC06a2765AaE2E0b
Upgrade Executor address:
0xCE659B798622B5BDa60572040375D8ec676C6Db6
Deployed at block number:
42802860



CHAIN ID
Don't worry about this; it's inconsequential for devnets. In production scenarios (which aren't yet supported), you'll want to use a unique integer identifier that represents your chain's network on chain indexes like Chainlist.org.

CHAIN NAME
This name provides a way for people to distinguish your Orbit chain from other Orbit chains. You'll want to make this a name that you can easily remember, and that your users and developers will recognize.

CHALLENGE PERIOD BLOCKS
The Challenge period (blocks) parameter determines the amount of time your chain's validators have to dispute—or "challenge"—the current state of the chain posted to your Orbit chain's base chain on L2 (Arbitrum Goerli or Sepolia for now; settlement to One and Nova mainnet chains isn't supported yet).

A longer challenge period means that your chain's nodes will have more time to dispute fraudulent states, but it also means that your chain's users will have to wait longer to withdraw their assets from your chain. This is one of the many tradeoffs that Orbit allows you to make when configuring your chain.

Note that the challenge period is measured in blocks on the underlying L1 chain, not the base (L2) chain. For example, if your Orbit chain settles to Arbitrum Sepolia, the challenge period window would be the number of Challenge period (blocks) multiplied by the L1 Sepolia block time (~12 seconds).

STAKE TOKEN
Your Orbit chain will be supported by at least one validator node. In order for your chain's validators to post assertions of the state of the chain on the base chain (L2), they're required to stake some value as a way to incentivize honest participation. This Stake token parameter specifies the token that your chain's validators must deposit into this contract when they stake. This is specified using the token's contract address on the L2 chain that your chain is settling to—Arbitrum Goerli or Arbitrum Sepolia—or 0x0000000000000000000000000000000000000000 if you want to use ETH as the stake token.

BASE STAKE
The Base stake parameter specifies the amount of the stake token (ETH or an ERC-20 token) that your chain's validators must deposit in order to post assertions of the state of your Orbit chain on the base chain's rollup contracts. This is specified using a float value.

If your Base stake is low, the barrier to participation will be low, but your chain will be more vulnerable to certain types of attacks.

For example, an Orbit chain with a base stake of 0.01 ETH could be halted by an adversary who can afford to deploy sacrificial validators that maliciously challenge every RBlock submitted to your Orbit chain's base chain.

The malicious challenges would result in slashed Orbit chain validators (one slashed validator per malicious challenge), but from the adversary's perspective, periodic slashing is just the price they have to pay to keep your chain offline.

A higher base stake incentivize honest participation by making it more expensive to launch these types of attacks. However, a higher base stake also translates to a higher barrier to entry for your chain's validators. This is another tradeoff to consider.

OWNER
This account address is responsible for deploying, owning, and updating your Orbit chain's base contracts on its base chain.

In production scenarios, this is a high-stakes address that's often controlled by a DAO's governance protocol or multisig. For your Orbit devnet chain, think of this as a low-stakes administrative service account.

Note that you'll have to fund this address with enough ETH to cover the gas costs of deploying your core contracts to L2.

When deploying your Orbit chain, this address must be a standard Ethereum wallet address (precisely speaking, an EOA); it can't be a smart contract/wallet contract.

GAS TOKEN
The Gas Token parameter specifies the token (ETH or an ERC-20 token) that is natively used for gas payments on the network. On Ethereum, Arbitrum One, and Arbitrum Nova the gas token is ETH. Orbit chains that are configured as AnyTrust chains can specify a different gas token as long as it falls within certain requirements.

The main requirement for custom gas tokens is that they are natively deployed on the parent chain. For example, if a team deploying an Orbit chain wants to use a specific ERC-20 as the gas token, that token must be deployed on the parent chain first (i.e. Arbitrum One or Nova). During chain deployment, that token is "natively bridged" and then properly configured as the native gas token on the new network.

There are other important considerations to keep in mind when deciding to use a custom gas token. Restrictions on the ERC-20 token include:

In this version, only tokens with 18 decimals are permitted to be the native token.
The token can't be rebasing or have a transfer fee.
The token must only be transferrable via a call to the token address itself.
The token must only be able to set allowance via a call to the token address itself.
The token must not have a callback on transfer, and more generally a user must not be able to make a transfer to themselves revert.
It is worth reiterating that currently this feature is only supported on Orbit AnyTrust chains. Additionally, using a gas token other than ETH adds additional overhead when it comes to ensuring chains are funded properly when posting data to their parent chain.

VALIDATORS
The first input field is an integer value that determines the number of validators that will support your initial deployment. Subsequent fields allow you to specify each of these validators' addresses.

The first validator address is randomly generated and can't be changed. Its private key will be automatically generated and stored within one of the JSON configuration files that will be generated in a moment.

Your chain's validators are responsible for validating the integrity of transactions and posting assertions of the current state of your Orbit chain to its base chain. In production scenarios, your Orbit chain would likely be hosted by a network of validator nodes working together. For your local Orbit chain, you can stick to the auto-generated single validator address.

Each of the validator addresses specified in this step will be added to an allow-list in one of your chain's base contracts, allowing them each to stake and validate transactions submitted to your Orbit chain.

BATCH POSTER
Your batch poster address is responsible for posting batches of transactions from your Orbit chain to its base contracts on its base chain. An address will automatically be generated for you; its private key will be automatically generated and stored within one of the JSON configuration files that will be generated in a moment.