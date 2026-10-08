# Kaspar File Format (`.kas`)

![Kaspar Compression Status](https://img.shields.io/badge/Compression-Lossy-red)
![Vibe Check Status](https://img.shields.io/badge/Vibe_Check-Severe_Depression-orange)
![License](https://img.shields.io/badge/License-Impractical-blue)

**Kaspar** is a revolutionary, highly experimental, and purely theoretical **Lossy Semantic Compression Standard** designed for whole software projects. It discards literal source code syntax entirely, replacing it with the structural "vibes," abstract intentions, and aesthetic feelings of the codebase.

When decompressed, a bound Large Language Model (LLM) hallucinates the project back into existence based on these semantic directives.

---

## Table of Contents
- [Core Mechanics](#core-mechanics)
- [Critical Constraints](#critical-constraints)
- [Getting Started](#getting-started)
- [Examples](#examples)
- [Compression Showcase](#compression-showcase)
- [Documentation](#documentation)
- [Contributing](#contributing)

---

## Core Mechanics

*   **The File Tree Manifest:** A hierarchical mapping of the project's structure, completely devoid of functional syntax or code snippets.
*   **Dynamic Compression Levels (1-100):** A metric dictating the verbosity of each file's description. Level 1 stores a detailed prompt of the logic; Level 100 stores extreme abstractions (e.g., "A script that does some database stuff but elegantly").
*   **Model Binding:** Mandatory metadata defining the exact LLM, system prompt, and temperature used during compression to ensure consistent hallucination upon extraction.

## Critical Constraints

To maintain standard compliance, Kaspar imposes the following strict requirements:

*   **Theatrical Decompression Delay (TDD):** A mandated artificial wait time during extraction, simulating complex builds via fake terminal logs, to ensure project managers believe the software took weeks to compile.
*   **Schrödinger’s Dependency:** The deliberate omission of at least one random package dependency, forcing the decompressing LLM to creatively hallucinate a replacement library.
*   **Vibe-Check Hashing:** A cryptographic checksum derived from a sentiment analysis score of the original developer's commit messages. If the hallucinated code is deemed "too optimistic" relative to the original baseline depression, the build fails.
*   **Artisanal Code Generation (ACG):** For files with a compression level exceeding 80, the model must rewrite core logic in an ancient language (e.g., Aramaic or Fortran) before translating it back, adding "historical robustness."

## Getting Started

The official mock CLI tool is provided in the `tools/` directory. It perfectly simulates the Kaspar decompression experience.

```bash
# Clone the repository
git clone https://github.com/b6d5b38e0d7ae6bd0d951815cd92df43/Kaspar.git
cd Kaspar

# Run the decompressor on a sample file
./tools/kaspar extract examples/hello_world.kas
```

## Examples

You can find examples of `.kas` archives in the `examples/` directory:
- [`examples/hello_world.kas`](examples/hello_world.kas): A simple hello world example showing basic compression.
- [`examples/GulfOfMexico.kas`](examples/GulfOfMexico.kas): A perfectly chaotic programming language where exclamation marks run code and arrays start at -1.
- [`examples/OSTRAJava.kas`](examples/OSTRAJava.kas): The entire OSTRAJava codebase compressed with Kaspar.

## Compression Showcase

The Kaspar protocol yields unparalleled efficiency by entirely omitting literal source code. Behold the file size reduction when comparing traditional archives against a Kaspar manifest for the OSTRAJava repository:

| Format | File Size |
| --- | --- |
| `OSTRAJava.zip` | 3.6 MB |
| `OSTRAJava.tar.gz` | 3.5 MB |
| **`examples/OSTRAJava.kas`** | **40 KB** |

That is an approximate **98.9%** reduction in file size, fully realizing the potential of Lossy Semantic Compression!

## Documentation

For the full, formal technical specification of the Kaspar standard, please refer to the academic LaTeX specification located in:
[`docs/RFC-KASPAR-0001.tex`](docs/RFC-KASPAR-0001.tex)

## Contributing

Contributions are welcomed! If you are a developer, project manager, or AI... you must not skip reading the [`CONTRIBUTING.md`](CONTRIBUTING.md) guide before submitting a PR.
Please also adhere to our [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).