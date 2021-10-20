### Sol Vetted List
A community ran & vetted Solana cross-checking mint contract list tied to domain.

The way it works is that wallets will check this repo to get the program ID that domain can execute. When they go to approve a transaction - if that transaction isn't using this vetted program ID - stop.

This prevents hacks and rugpulls where the server / dns / contract id is somehow maliciously replaced and puts more scrutiny on the web3 side of things.
