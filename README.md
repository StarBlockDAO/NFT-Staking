# NFT-Staking

All the contracts for NFT staking and Wrapped NFT.

# NFTMasterChef Contract
NFTMasterChef is the core contract of NFT staking and contains the main logic of staking NFT: reward and dividend. Every NFT Collection will have a pool in NFTMasterChef, which is responsible for ditributing the StarBlock Token: STB to all the staked NFTs in the pool.

# WrappedNFTFactory
WrappedNFTFactory is the contract to deploy Wrapped NFT Collection, which is used to wrap NFT. Every NFT contract will have a Wrapped NFT contract and every token ID in NFT collection can be wrapped to an Wrapp NFT in the Wrapp NFT collection with the same token ID. Also the Wrapp NFT can be unwapped to the NFT with the same token ID anytime without any permission. If you own a Wrapped NFT, you own the NFT with the same token ID indirectly which is managed by the Wrapped NFT contract. Nobody can unwrapped an Wrapped NFT without a NFT with the same token ID.

# NFTUtils Contract
NFTUtils is a multi-reading contract for the data in NFTMasterChef and other contracts, which is used for the frontend to merge multi-calls.

# Deployment

We have deployed them on the Ethereum Mainnet: 

WrappedNFTFactory: https://etherscan.io/address/0x6df4A699Ac7086Ee4a8d0602F2D00A0054a0930A

NFTMasterChef: https://etherscan.io/address/0xBbF9CC5DeCDB8e1d9895b7d98793136798BD512E

NFTUtils: https://etherscan.io/address/0x106257002ad21bc2d8C3391186Fe8c9121F88C40

