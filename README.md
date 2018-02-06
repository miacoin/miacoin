Algorithm 	Scrypt
Type 	PoW/PoS
Coin name 	Miacoin
Coin ticker 	MIAC
Address letter 	M
Date Created 	01/01/2018
RPC port 	32486
P2P port 	32485
Last PoW block 	block 1000
Block reward 	815 coins (PoW)
PoS percentage 	20% per year
Target spacing 	64 seconds
Coinbase maturity 	10 blocks
Transaction confirmations 	6 blocks
Coin Max supply 	342.300.000 Miacoin (MIAC)

============================
Miacoin development tree

Miacoin is a Pow - PoS -based cryptocurrency.

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Miacoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.

------------------------------------------------------------------------------

Building Miacoin

See doc/readme-qt.rst for instructions on building Miacoin Qt, the intended-for-end-users, nice-graphical-interface, reference implementation of Miacoin.

See doc/build-*.txt for instructions on building Miacoind, the intended-for-services, no-graphical-interface, reference implementation of Miacoin.
