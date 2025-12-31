# Hi, I'm JD McIntosh 👋

**Systems Programmer | x86_64 Assembly & Low-Level C Specialist**

Location: The South  
Twitter/X: [@EdistoKato](https://x.com/EdistoKato)

I'm a low-level developer focused on **hand-written x86_64 assembly** and **performance-critical C** for Linux systems. My projects are useful for embedded, firmware, kernel, or optimization work.

### Skills & Expertise
- **x86_64 Assembly Language** (NASM): Deep knowledge of the System V AMD64 ABI, registers, calling conventions, stack management, and optimization techniques.
- **Low-Level C**: Building shared libraries, custom data structures, recursive algorithms, and memory-safe code (Valgrind-clean).
- **Data Structures & Algorithms**: Pure assembly implementations of balanced trees, dynamic structures, and utilities.
- **Systems Programming**: Dependency-free designs ideal for constrained environments—no external libs (with exception of libc).
- Proven memory safety and correctness in complex, recursive code.

### Highlighted Projects

[![BTree](https://img.shields.io/badge/BTree-Assembly-blue)](https://github.com/KatoKode/BTree)  
**Single-Threaded B-Tree in x86_64 Assembly**  
Fully functional B-Tree with insertion, deletion, search, and rebalancing—all in assembly. C interface as a shared library. Benchmarks: ~350k–590k ops/sec depending on order. Valgrind-clean.

[![RBTree](https://img.shields.io/badge/RBTree-Assembly-yellow)](https://github.com/KatoKode/RBTree)  
**Red-Black Tree in x86_64 Assembly**  
Classic RB-Tree with rotations, coloring, and full operations implemented from scratch in assembly. Clean C API.

[![ByteBuffer](https://img.shields.io/badge/ByteBuffer-Assembly-darkred)](https://github.com/KatoKode/ByteBuffer)  
**Fixed-Size ByteBuffer in x86_64 Assembly**  
Bounds-checked byte buffer (84% assembly) with get/put for primitives (int16–64, float/double, varchar, bytes). Little-endian serialization, mark/reset/flip, shared library, and configurable C demo.

[![JSON](https://img.shields.io/badge/JSON-Assembly%20%2B%20C-darkgreen)](https://github.com/KatoKode/JSON)  
**High-Performance JSON Parser/Builder**  
Lightweight, dependency-free JSON library with assembly optimizations for tokenization and parsing. Supports nested objects/arrays. 100% Valgrind-clean.

[![x86_64 Tutorial](https://img.shields.io/badge/Tutorial-Assembly-orange)](https://github.com/KatoKode/x86_64_Assembly_Language_Tutorial)  
**Practical x86_64 Assembly Tutorial**  
Step-by-step guide building a real shared library (`libutil.so`) from assembly sources. Covers ABI, linking, and integration with C.

Other repos: Stack, Queue, List all in assembly with C wrappers.

### Why Low-Level?
I enjoy working close to the hardware. These projects showcase production-grade techniques: correctness proofs, benchmarks, memory safety, and real-world usability.

Open to opportunities in **embedded systems**, **firmware**, **kernel development**, **high-performance computing**, or any role valuing assembly and systems expertise.

Feel free to star ⭐ or fork—thanks for visiting!

— JD
