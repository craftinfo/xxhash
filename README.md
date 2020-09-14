# xxhash

mulle-sde craftinfo for [xxHash](//github.com/Cyan4973/xxHash) "Extremely fast non-cryptographic hash algorithm"

```
mulle-sde dependency add --c --scm git --address xxhash --branch release --github Cyan4973 xxHash
mulle-sde dependency mark xxhash singlephase 
mulle-sde dependency set xxhash include xxhash/xxhash.h
mulle-sde environment --global set MULLE_CRAFT_USE_SCRIPT YES
```
