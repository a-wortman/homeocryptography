# Homeopathic Encryption
Homeopathic encryption is a new block cipher over one-byte blocks. It's founded in the tried-and-true science of homeopathy: by dividing bits into smaller and smaller parts, eventually an entire message is enciphered. The system is, clearly, unbreakable, since only the intended recipient would know which bits to reconstitute the original message from.

Encryption can be conducted with the file `encrypt.py`, relying only on `python` being present. Decryption is left as an exercise to the reader.

As encryption is stronger when you encrypt more times, there is support in this cipher for multiple "rounds" of encryption - the default is 1, and maximum strength encryption is obtained around 2- or so rounds. Obviously, this property of the homeopathic encryption cipher is substantiated just the same by simple facts of homeopathy: by dilluting a sample further, its efficacy increases.

####ps this isn't serious and everything here was committed april 1 (april fool's day)
####also this "encryption" isn't reversible, it ambiguosly maps most bytes to `0xff`, `0x55`, or `0xaa`, but also maps `0x00` to `0x00`. it's quite terrible.
