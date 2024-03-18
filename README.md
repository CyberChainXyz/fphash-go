# fphash

fphash is a variant of [Cryptonight-GPU](https://ryo-currency.com/cn-gpu/) algorithm, with parameters below:

```
MEMORY = 32 * 1024
ITER = 0x300
```

This project provides Go bindings for the original C++ implementation of the Cryptonight-GPU algorithm can be found at [ryo-currency/ryo-currency](https://github.com/ryo-currency/ryo-currency/tree/master/src/crypto/pow_hash).


## Usage

To use these bindings in your Go project, import the package:

```go
import "github.com/CyberChainXyz/fphash"

intput := []uint8{1, 2, 3, 4, 5}
result := fphash.Hash(input) // [32]uint8
```