# I'm JD McIntosh and here you can find some information on my skills and links to DSA and other implementations I've created.

**Systems Programmer | x86_64 Assembly & Low-Level C Specialist <img src="computer.svg" alt="Low-level computer" width="20"/> <img src="gear.svg" alt="Low-level gear" width="20"/> <img src="rocket.svg" alt="Low-level rocket" width="20"/>**

Location: The South

I'm a low-level developer focused on **x86_64 assembly** and **performance-critical C** for Linux systems. My projects are useful for embedded, firmware, kernel, or optimization work.

### Skills & Expertise
- **x86_64 Assembly Language** (NASM): Deep knowledge of the System V AMD64 ABI, registers, calling conventions, stack management, and optimization techniques.
- **Low-Level C**: Building shared libraries, custom data structures, recursive algorithms, and memory-safe code (Valgrind-clean).
- **Data Structures & Algorithms**: Pure assembly implementations of balanced trees, dynamic structures, and utilities.
- **Systems Programming**: Dependency-free designs ideal for constrained environments—no external libs (with exception of libc).
- Proven memory safety and correctness in complex, recursive code.

### Highlighted Projects

[![SRDB](https://img.shields.io/badge/SRDB-C++14-gold)](https://github.com/KatoKode/SQL-Relational-Database-System)
**Lightweight Client-Server RDBMS in C++14**
SQL engine with persistent B+Tree storage, persistent JSON schema, recursive-descent parser, bytecode VM, multi-threaded TCP server, encryption (libgcrypt), authentication, privileges, and ncurses client. Supports CREATE/ALTER/DROP, JOINs, subqueries, indexes, foreign keys, LOAD/SOURCE, and more. Valgrind-clean, secure systemd deployment. 🔧

[![BTree](https://img.shields.io/badge/BTree-Assembly-darkcyan)](https://github.com/KatoKode/BTree)
**Single-Threaded B-Tree in x86_64 Assembly**
Fully functional B-Tree with insertion, deletion, search, and rebalancing—all in assembly. C interface as a shared library. Benchmarks: ~350k–590k ops/sec depending on order. Valgrind-clean. 🚀

[![BTree Library](https://img.shields.io/badge/BTree%20Library-Assembly-gold)](https://github.com/KatoKode/BTree-Library)
**Single-Threaded B-Tree in x86_64 Assembly**
Fully functional B-Tree with insertion, deletion, search, and rebalancing—all in assembly. C interface as a shared library. Benchmarks:🔥 4.11M deletes/sec🔥 2.19M inserts/sec 🔥 2.78M mixed insert/delete ops/sec 🔥 8.4M keys bulk load: 0.008s. Valgrind-clean. 🚀

[![Kato DSA](https://img.shields.io/badge/Kato%20DSA-High%20Perf-darkcyan)](https://github.com/KatoKode/kato-dsa)
**High-performance B-Tree in x86_64 Assembly + Python wrapper for Linux**
Fully balanced B-Tree with custom callbacks, insert/search/delete, in-order traversal. Bundled native `.so` libraries for Linux x86_64. Valgrind-clean core. Installable via `pip`. Benchmarks coming soon. 🚀

[![RBTree](https://img.shields.io/badge/RBTree-Assembly-gold)](https://github.com/KatoKode/RBTree)
**Red-Black Tree in x86_64 Assembly**
Classic RB-Tree with rotations, coloring, and full operations implemented from scratch in assembly. Clean C API. 🚀

[![ByteBuffer](https://img.shields.io/badge/ByteBuffer-Assembly-darkcyan)](https://github.com/KatoKode/ByteBuffer)
**ByteBuffer in x86_64 Assembly**
Bounds-checked byte buffer (84% assembly) with get/put for primitives (int16–64, float/double, varchar, bytes). Little-endian serialization, mark/reset/flip, shared library, and configurable C demo. 🚀

[![JSON](https://img.shields.io/badge/JSON-Assembly%20%2B%20C-gold)](https://github.com/KatoKode/JSON)
**High-Performance JSON Parser/Builder**
Lightweight, dependency-free JSON library with assembly optimizations for tokenization and parsing. Supports nested objects/arrays. 100% Valgrind-clean. 🚀

[![List](https://img.shields.io/badge/List-Assembly-darkcyan)](https://github.com/KatoKode/List)
**Dynamic Array/List in x86_64 Assembly**
High-performance growable list with insert/search/delete/sort, bidirectional iteration, and direct indexing—all hand-written in assembly. Clean C interface as a shared library. Valgrind-clean. 🚀

[![x86_64 Tutorial](https://img.shields.io/badge/Tutorial-Assembly-gold)](https://github.com/KatoKode/x86_64_Assembly_Language_Tutorial)
**Practical x86_64 Assembly Tutorial**
Step-by-step guide building a real shared library (`libutil.so`) from assembly sources. Covers ABI, linking, and integration with C. 🚀

[![Queue](https://img.shields.io/badge/Queue-Assembly-darkcyan)](https://github.com/KatoKode/Queue)
**Queue in x86_64 Assembly**
This is an Assembly Language implementation of a Queue (FIFO). The Queue is implemented as a shared-library with a C interface. 🚀

[![IO](https://img.shields.io/badge/IO-Assembly-gold)](https://github.com/KatoKode/IO)
**File operations written in x86_64 Assembly with a C interface as a Shared-Library. Designed for performance-critical applications that need direct I/O (O_DIRECT), synchronized writes (O_DSYNC).**

[![Queue](https://img.shields.io/badge/Stack-Assembly-darkcyan)](https://github.com/KatoKode/Stack)
**Stack in x86_64 Assembly**
Stack (LIFO) Implementation in x86_64 Assembly Language with C Interface as a Shared Library.

---

Open to opportunities in **kernel development**, **high-performance computing**, or any role valuing assembly and systems expertise.

Feel free to star ⭐ or fork—thanks for visiting!

— JD
