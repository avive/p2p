# Eth p2p learning research notes

## guides / docs

https://github.com/ethereum/go-ethereum/wiki/Peer-to-Peer

https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol
https://github.com/ethereum/devp2p/blob/master/rlpx.md
https://github.com/ethereum/wiki/wiki/Whisper
https://github.com/ethereum/wiki/wiki/libp2p-Whitepaper (seems outdated)

https://github.com/ethereum/devp2p/blob/master/rlpx.md

https://godoc.org/github.com/ethereum/go-ethereum/p2p

https://github.com/ethereum/go-ethereum/wiki/Connecting-to-the-network


### Nodes Discovery
https://github.com/ethereum/devp2p/blob/master/rlpx.md#node-discovery

v5 discovery protocol
https://blog.ethereum.org/2016/11/17/whoa-geth-1-5/

## bzz

## RLPX
https://github.com/fjl/go-ethereum/tree/rlpx-framing/p2p/rlpx
https://github.com/ethereum/devp2p/blob/master/rlpx.md


## code
- p2p go package in go-eth
- https://github.com/nolash/go-ethereum-p2p-demo
- The 'eth' p2p protocol: https://github.com/ethereum/go-ethereum/blob/master/eth/protocol.go
- les - light eth sub-protocol: https://github.com/zsfelfoldi/go-ethereum/blob/light/les/protocol.go 

## Community
- https://gitter.im/ethereum/devp2p
- https://gitter.im/ethereum/whisper
- https://gitter.im/ethereum/swarm

## Random Notes
It's a bit like the relationship between TLS and HTTP: RLPx is the encrypted transport protocol, devp2p defines how we use it.
devp2p is this: https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol
rlpx is how devp2p messages are encrypted and transported

In which ways similar to the p2p protocol of BitTorrent and other file sharing programs,
and in which ways different?


https://github.com/ethereum/EIPs/pull/49


