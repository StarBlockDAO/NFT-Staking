# NFT-Staking

All the contracts for NFT staking and Wrapped NFT on StarBlock DAO.

# NFTMasterChef Contract
NFTMasterChef is the core contract of NFT farming on StarBlock DAO and contains the main logic of staking NFT: reward and dividend. Every NFT Collection will have a pool in NFTMasterChef, which is responsible for distributing the StarBlock Token: STB to all the staked NFTs in the pool.

# WrappedNFTFactory Contract
WrappedNFTFactory is the contract to deploy Wrapped NFT(short as WNFT) Collection contract on StarBlock DAO, which is the wrapped collection of original NFT collection. Wrapped NFT is equivalent to the original NFT and can be traded arbitrarily, 1 WNFT = 1 Original NFT.

# NFTUtils Contract
NFTUtils is a multi-reading contract for the data in NFTMasterChef and other contracts, which is used for the frontend to merge multi-calls.

# Deployment

We have deployed them on the Ethereum Mainnet: 

WrappedNFTFactory: https://etherscan.io/address/0x6df4A699Ac7086Ee4a8d0602F2D00A0054a0930A

NFTMasterChef: https://etherscan.io/address/0xBbF9CC5DeCDB8e1d9895b7d98793136798BD512E

NFTUtils: https://etherscan.io/address/0xcb8a0e48353b1382383fc4a2deaba5a684cb857b

