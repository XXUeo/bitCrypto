# bitCrypto
bticoin's cryptography workflow is extracted in this repo

go to secp256k1 then.
<br>
$./autogen.sh<br>
$ ./configure <br>
$ make<br>
$ make install
</br>
https://www.toshblocks.com/bitcoin/compile-bitcoin-source-code-ubuntu-16-04-lts/
good stuff to setup bitcoin in unix

</br>
### For byteswap:
Darwin features; we include a check for bswap_16 because if it is already defined, protobuf has
// defined these macros for us already; if it isn't, we do it ourselves. In either case, we get the exact same
// result regardless which path was taken.
</br>
=============
</br>

### sha256
https://www.thesslstore.com/blog/difference-sha-1-sha-2-sha-256-hash-algorithms/
https://en.wikipedia.org/wiki/SHA-2
https://bitcointalk.org/index.php?topic=146191.0
https://stackoverflow.com/questions/14356526/whats-the-difference-between-the-hash-algorithms-sha-2-and-sha-3

### ripe-md160
https://en.wikipedia.org/wiki/RIPEMD

### privatekey
**
 * secure_allocator is defined in allocators.h
 * CPrivKey is a serialized private key, with all parameters included (279 bytes)
  */

### generation of private key
wallet.cpp:126 GenerateNewKey -> key.cpp:126 MakeNewKey ->keydata

### fetch new private key
key.cpp:134 CKey::GetPrivKey() ->  CPrivKey privkey; ->ec_privkey_export_der
