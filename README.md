Source: This is a fork of this dude's original work : [ntmoe](https://github.com/ntmoe)

Diceware
========

This is a Python implementation of the [Diceware](http://world.std.com/~reinhold/diceware.html) pasword-generating algorithm. It uses uses `/dev/urandom` or
equivalent using calls within Python's `random` module.

How to use diceware-v2
----------
(My modified version to work better for combining w/ xsel and getting a nice diceware 
password copied to the clipboard when used w/ a bash command)

1. You may need to set some permissions first.

        $ chmod u+x diceware-v2

2. Run the program:

        $ ./diceware-v2 -w n

    where `n` is the number of words you want in your passphrase. The passphrase is printed to the terminal.

How to use diceware (orig)
----------

1. You may need to set some permissions first.

        $ chmod u+x diceware

2. Run the program:

        $ ./diceware -w n

    where `n` is the number of words you want in your passphrase. The passphrase details are printed to the terminal.

Caveats
-------

I'm not an expert in security or cryptography. If you want this to be more secure, use physical dice (or some other offline method of random number generation) to generate your passphrase the old-skool [_sic_] way.
