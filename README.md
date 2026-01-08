### <code> user@0xMilanecha:~$ ./init_profile.sh </code>

# [ 0xMilanecha ]
> **Systems Engineer & Memory Research Hobbyist.**
> *I like videogames.*

---

### 📡 System Status
I am an independent researcher driven by the challenge of **Binary Instrumentation** and **Kernel-Level Analysis**. My work exists because there´s a guy better than me.

* **Focus:** Writing code that touches physical memory without the OS knowing.
* **Philosophy:** "If you can reconstruct the SDK, you own the engine."

---

### 🛠 The Arsenal

| **Low-Level Core** | **High-Level Infrastructure** |
| :--- | :--- |
| `C++20` (Templates / Meta-programming) | `Java` (Netty / High-Concurrency) |
| `x86_64 Assembly` (Shellcode / Thunks) | `Python` (Capstone / Automation) |
| `Verilog` (FPGA Logic) | `Spring Boot` (Auth / Distribution) |

| **Engine Targets** | **Reverse Engineering Suite** |
| :--- | :--- |
| **Source 2** (Schema System / VScript) | `IDA Pro 8.x` / `Ghidra` |
| **Unreal Engine 5** (UWorld / GObject) | `WinDbg` (Kernel Mode) |
| **Unity** (IL2CPP Metadata) | `ReClass.NET` / `PCIe Leech` |

---

### 🚀 PoF ("Public") - ABANDONED

#### 🛰️ [EFT-DMA-Radar](https://github.com/Milanecha/eft-dma-radar)
`[STATUS: ABANDONED]` `[TYPE: HARDWARE]`
A zero-footprint spatial awareness tool for **Escape from Tarkov**.
* **PCIe Logic:** Implemented custom **TLP throttling** to keep bus activity below heuristic detection thresholds.
* **Throughput:** Utilization of **Scattered Read/Write** operations for batch processing large entity lists (`LocalGameWorld`) without stalling the bus.
* **Architecture:** Zero-copy pipeline; raw memory structs are piped to a **Netty-based (Java)** backend for ultra-low latency external rendering.
* **Sync:** Bi-linear interpolation for GameWorld-to-Map coordinate translation.

#### 🎯 [CS-Internal-Framework](https://github.com/Milanecha/cs-internal)
`[STATUS: ABANDONED]` `[TYPE: INTERNAL]`
Modular instrumentation framework for **Counter-Strike 2**.
* **Dynamic Analysis:** Runtime parser for the **Source 2 Schema System**, eliminating the need for hardcoded offsets.
* **Hooking:** **Shadow VMT** placement in `.data` sections to bypass standard `.rdata` integrity checks.
* **Rendering:** DX11 hook implementing **State-Block preservation** to prevent overlay flickering and context corruption.
* **Stealth:** CRT-Free environment; imports resolved via **PEB walking** and custom syscall wrappers.

#### 🛡️ [Valorant-Security-Lab](https://github.com/Milanecha/val-security-lab)
`[STATUS: ABANDONEN-DETECTED]` `[TYPE: POST-MORTEM]`
A technical autopsy of the **Vanguard (VGK)** user-mode environment.
* **The Approach:** Attempted a Kernel-User shared memory bridge via IRP hooking.
* **The Failure:** Flagged due to **CR3 register cache invalidation** delays during manual context switching, leading to timing discrepancies.
* **Forensics:** Post-ban analysis confirmed **PTE** flag manipulation triggered a generic heuristic scan.

#### ⚙️ [Unity-SDK-Gen](https://github.com/Milanecha/unity-sdk-gen)
`[STATUS: ACTIVE]` `[TYPE: AUTOMATION]`
Automated metadata reconstruction for **IL2CPP** titles (Rust, Tarkov).
* **Core:** Traverses `global-metadata.dat` to reconstruct `MethodInfo` chains and `TypeDefinitions`.
* **Alignment:** Auto-generates C++ structs with **correct padding** and alignment for direct memory casting in the internal cheat.
* **Resilience:** Signature matching for obfuscated field names across game updates.

---

### 🔮 Current Focus
* **LLVM Obfuscation:** Writing custom compiler passes to generate unique assembly signatures per build.
* **TPM 2.0:** Researching hardware identification routines in modern ACs.

---

### 🔌 Connect
* **Discord:** `Milanesa`
* **GitHub:** `github.com/Milanecha`

<p align="right">
  <code>0x4D 0x69 0x6C 0x61 0x6E 0x65 0x63 0x68 0x61</code>
</p>
