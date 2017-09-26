# bitCrypto
bticoin's cryptography workflow is extracted in this repo

go to secp256k1 then.
<br>
$./autogen.sh<br>
$ ./configure <br>
$ make<br>
$ make install


<br/>
bitcoin's byteswap and endian in /crypto is using https://github.com/google/protobuf.</br>
</br>
However:
Darwin features; we include a check for bswap_16 because if it is already defined, protobuf has
// defined these macros for us already; if it isn't, we do it ourselves. In either case, we get the exact same
// result regardless which path was taken.
</br>
=============
</br>
https://www.toshblocks.com/bitcoin/compile-bitcoin-source-code-ubuntu-16-04-lts/
good stuff to setup bitcoin in unix
