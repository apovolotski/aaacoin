AAAcoin Core
=====================================

https://aaacoin.us

What is AAAcoin?
----------------

AAAcoin is a digital currency, similar to Bitcoin, that was developed for marijuana enthusiasts.
The currency was created in January 2014 and relaunched as AaaCoinGold in January 2017.

AAAcoin Core is the name of open source software which enables the use of this currency.
It is based on Bitcoin Core 0.12.1 with some features backported from Bitcoin Core 0.13.x and 0.14.0.

Our mission is to provide this billion dollar industry with alternative payment and advertising resources.
Thank you for joining us on the AAAcoin adventure!


License
-------

AAAcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested and is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/apovolotski/aaacoin/tags) are created regularly to indicate new official, stable release versions of AAAcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Coin Specifications
----------------

- Total: 138,600,000 AAA
- Algorithm: POSV3
- POS reward: 25 AAA
- Block time: 60 seconds
- P2P port: 22225
- RPC port: 22226

Builds
----------------

v.1.1.0.0:

- Rebased to Bitcoin Core 0.12.1
- BIP32 HD wallet support
- Added autocomplete to AAAcoin-Qt console window
- Added toggle for unmasking password
- Block hash changed back to SHA256D
