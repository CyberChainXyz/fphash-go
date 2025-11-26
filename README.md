[![Test](https://github.com/CyberChainXyz/fphash-go/actions/workflows/test.yml/badge.svg)](https://github.com/CyberChainXyz/fphash-go/actions/workflows/test.yml)
[![Go Reference](https://pkg.go.dev/badge/github.com/CyberChainXyz/fphash-go.svg)](https://pkg.go.dev/github.com/CyberChainXyz/fphash-go)

# fphash

`fphash` is a GPU-friendly Proof-of-Work algorithm designed specifically for [CyberChain](https://cyberchain.xyz/). Inspired by Cryptonight-GPU.

*   **ASIC/FPGA Resistance:** Heavily utilizes the efficient floating-point units of modern GPUs, making hardware implementation on FPGAs or ASICs difficult and expensive.
*   **Broad Compatibility:** Designed with a low memory footprint to enable participation across a wide range of GPU models.
*   **Fast Verification:** Optimized for rapid verification, significantly reducing the load on network nodes.

## Usage

To use these bindings in your Go project, import the package:

```go
import "github.com/CyberChainXyz/fphash-go"

intput := []uint8{1, 2, 3, 4, 5}
result := fphash.Hash(input) // [32]uint8
```
