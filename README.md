<div align="center">

# Variably Constant

**High-performance Rust tools and libraries, bound to multiple languages.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)](https://www.rust-lang.org/)

</div>

---

We create high-performance systems tools in Rust and expose them through clean bindings to multiple languages. The focus is practical, low-overhead interoperability — especially for PowerShell, Python, C, and .NET — while keeping the core implementation fast and reliable in Rust.

Most PowerShell modules are built with **[PWRS (PoWerRuSt)](https://github.com/Variably-Constant/PWRS)** and support both Windows PowerShell 5.1 and PowerShell 7.4+.

---

## Highlighted Projects

### [PWRS (PoWerRuSt)](https://github.com/Variably-Constant/PWRS)
Rust bindings for writing PowerShell binary modules, in the spirit of PyO3.  
**Languages / runtimes:** Rust · PowerShell 7.4+ · Windows PowerShell 5.1  
No .NET SDK required. Cmdlets, classes, providers, and more are defined in Rust and compiled into native modules.

### [trex](https://github.com/Variably-Constant/trex)
Token-Regular EXpression — a regex-shaped pattern language over typed tokens, evaluated by derivatives.  
**Languages / interfaces:** Rust · Python · PowerShell · CLI  
Supports typed token matching, rewrites, redaction, and high-performance scanning without backtracking.

---

## Other Public Projects

| Project | Description | Languages / Interfaces |
|---------|-------------|------------------------|
| **[UAST-Grep](https://github.com/Variably-Constant/UAST-Grep)** | High-performance cross-language AST search and SAST tool powered by tree-sitter (~3,873 rules across 71 languages). | Rust · Python · .NET · CLI |
| **[SubEtha](https://github.com/Variably-Constant/SubEtha)** | Cross-context channel over memory-mapped files. Lock-free, adaptive, and disk-persistent. | Rust · C · Python · PowerShell |
| **[Flynnel](https://github.com/Variably-Constant/Flynnel)** | K-aware, NUMA-aware work-stealing scheduler with extended Flynn taxonomy dispatch. | Rust |
| **[Wgpu](https://github.com/Variably-Constant/Wgpu)** | GPU compute, rendering, and shader tools for PowerShell via wgpu. | PowerShell · Rust |
| **[SecureFetch](https://github.com/Variably-Constant/SecureFetch)** | HTTPS from PowerShell over TLS 1.3 with X25519MLKEM768 post-quantum hybrid key exchange. | PowerShell |
| **[Zstd](https://github.com/Variably-Constant/Zstd)** | Zstandard compression module for PowerShell. | PowerShell |
| **[PWRS-GUI](https://github.com/Variably-Constant/PWRS-GUI)** | Windows, dialogs, and grids for PowerShell, rendered on the GPU. | PowerShell |
| **[PWRSWriteColorEX](https://github.com/Variably-Constant/PWRSWriteColorEX)** | Colored and styled console output for PowerShell. | PowerShell |

---

## Approach

- High-performance cores written in modern Rust
- First-class bindings to PowerShell, Python, C, and .NET where useful
- Minimal external dependencies and practical performance focus
- MIT-licensed open source

---

## Contributing

Issues and pull requests are welcome. Most repositories include tests and follow standard Rust practices. See individual project READMEs for details.

---

## Contact

- **Email**: [mark@variablyconstant.com](mailto:mark@variablyconstant.com)
- **GitHub**: [github.com/Variably-Constant](https://github.com/Variably-Constant)

---

*Variably Constant — high-performance Rust tools, bound to the languages you use.*
