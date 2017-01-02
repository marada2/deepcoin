Deepcoin
================================

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2014 Deepcoin Developers

Deepcoin Vital Statistics
----------------

 - 5 rounds of hashing (luffa, cubehash, shavite, simd, echo)
 - 1 minute block targets
 - Block reward starts at 512 coins a block
 - First subsidy halves at 43,200, subsidy halving gap will then be 86,400, after which the gap grows by 43,200
 - Maximum coins will be 99,000,000
 - Hardened Nite's Gravity Well running from start to manage block target and rule out any instamine
 - Block time will be 2 minutes after block 2,841,200 for incresed TX fees in block after last block reward
 - Lowest possible difficulty raised much higher to 1/2^6 from the very low default Scrypt based limit of 1/2^12
 - Client port 22871 for testnet 32871
 - RPC port 22872 for testnet 32872
 
For more information please go to http://deepcoin.biz.

License
-------

Deepcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Warning
----------------
This is an experimental repository and it is not intended for normal usage.
Please use with special care.
If you were looking for official Deepcoin client, please visit:
https://github.com/Deepcoinbiz/Deepcoin

How to build experimental version with stealth address feature enabled
----------------
Please make sure you have installed following packages:
qt4-qmake libqt4-dev libdb5.1++-dev g++ libleveldb-dev libssl-dev libboost-all-dev

git clone https://github.com/marada2/deepcoin/<br>
cd deepcoin<br>
git checkout new-sx-0.8.7<br>
qmake-qt4<br>
make<br>

Precompiled binaries
----------------
To get the precompiled binaries please visit:
https://github.com/marada2/deepcoin-binaries

Or download from http://dcn.deeptech.pw/
