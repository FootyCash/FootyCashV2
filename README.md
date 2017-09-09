
FootyCash development tree

FootyCash is a PoS-based cryptocurrency.

FOOTYCASH is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

Total POW: 100 Blocks
POW Reward: 1 XFT per Block
POS Reward: 1 XFT (HiPOS)
Block Spacing: 60 Seconds
Diff Retarget: 24 Blocks
Maturity: 188 Blocks
Stake Minimum Age: 8 Hours

40 MegaByte Maximum Block Size (40X Bitcoin Core)

Port: 17017
RPC Port: 17018

Magic Bytes: 0x17 0x24 0x08 0x32


FOOTYCASH includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the FOOTYCASH codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.


