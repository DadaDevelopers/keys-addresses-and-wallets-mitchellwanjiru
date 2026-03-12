[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TcqVPkuA)
# assignment-2

Generate legacy addresses, bech32 addresses and bech32m addresses

What is the difference between hardened and non hardened keys
Hardened keys act as a firewall. If a child key is leaked, the parent private key remains safe. Non hardened keys allow the parent public key to derive all child public keys.
Why should a wallet developer prefer deterministic wallets over non deterministic wallets
Deterministic wallets are preferred because you only need to backup one seed to recover every address ever created. In non-deterministic wallets, you'd have to backup the wallet every single time you generated a new address
