# Cryptex Bank Inc. - Cryptocurrency Payments Bank

=====================================

Cryptocoin Name - CryptexBlue (CXB)

Network - Non-standard Bitcoin Network

Encryption Framework - Private Blockchain Network (PPKGV9917, 9918)

Warning - Bitcoin Blockchain cannot be connected to trading / exchange network.

https://cryptexblue.com/

What is CryptexBlue (CXB)?
----------------

CryptexBlue (CXB) is a digital currency that enables instant payments to
anyone, anywhere in the world using encrypted channel of cryptexbank's own bitcoin node network. CryptexBlue (CXB) of Cryptex Bank Inc. doesn't use P2P technology anymore. To operate
with a central authority: managing transactions and issuing money are carried
out collectively by the anti-node network as the system is now implemented to not to run on P2P channel. Cryptex doesn't use Miners any more and that the blockcypher processing is done on a hidden channel as published in the bitcoin 6.0 whitepaper. CryptexBlue (CXB) Core is the name of open source
software which enables the use of this currency. CryptexBlue's servers use military grade multi-level encryption to provide enhanced security in which both
Bitcoin (BTC) and Cryptexblue (CXB) blocks travel through the global encrypted blockchain network. Online payment of bitcoins happen through dedicated bitcoin payment channel 
at https://bitcoin.cryptexblue.com. Encryption applied is AES-256 with CCM/CGM with 4096 bit (RSA+SHA2). Underlying node transport system uses SHA 256, 
and the elliptic curves P-256 and P-521. The code base is derived from Bitcoin core and Cryptexblue (CXB) uses the master repo of bitcoin and the excryption standards applied on this core are custom with algo codes ppkgvsea9917, ppkdvsea9918 respectively.

For more information, as well as an immediately usable, readable version of
the CryptexBlue (CXB) Core application, see https://cryptexblue.com/about.html

Whitepaper
-------
Bitcoin 6.0 framework whitepaper co-authored by Dr. Yuvraj Kumar and Satoshi Nakamoto can be downloaded from this link: https://www.cryptexblue.com/assets/whitepaper/Military_Grade_e-Payment_System_v1.0.pdf. Please note this document is the property of the respective author / co-author and of the licensing partners. The whitepaper is released in as is condition and usage of it should be rightly referred to or citations must be provided. Cryptexblue payment system is based on Bitcoin 6.0 framework as mentioned above. 

License
-------

CryptexBlue (CXB) Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built (see `doc/build-*.md` for instructions) and tested, but it is not guaranteed to be
completely stable. [Tags](https://github.com/CryptexBlue/CryptexBlue/tags) are created
regularly from release branches to indicate new official, stable release versions of CryptexBlue (CXB) Core.

Release branches and tags do not exist, so please do not fork
that repository unless it is for development reasons.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations are not accepted as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
