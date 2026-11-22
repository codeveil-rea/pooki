# CapCut.exe Decoded Binary & Structure Report

This directory contains the decoded headers, memory mapping, sections, imported DLL dependencies, and extracted string tables of the official **CapCut.exe** binary (`v9.8.0.4213`).

---

## 1. Binary Identification

| Property | Value |
| :--- | :--- |
| **File Name** | `CapCut.exe` |
| **Target Architecture** | `AMD64 / x86_64` (64-bit Intel/AMD) |
| **Format** | `PE32+` (Portable Executable) |
| **Subsystem** | `IMAGE_SUBSYSTEM_WINDOWS_GUI` |
| **File Size** | `90,536 bytes` (90.5 KB) |
| **Image Base** | `0x140000000` |
| **Entry Point RVA** | `0x00004E30` (`0x140004E30`) |
| **PDB Companion** | `CapCut.pdb` (`8bba7091-afe8-486c-af8c-2f54b31fba63`) |

---

## 2. Decoded Section Headers

| Section | Virtual Address | Virtual Size | Raw File Pointer | Raw Size | Characteristics / Permissions |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **`.text`** | `0x00001000` | `0x5A1C` | `0x00000400` | 23,552 B | `0x60000020` (Executable, Readable, Code) |
| **`.rdata`** | `0x00007000` | `0x40FA` | `0x00006000` | 16,896 B | `0x40000040` (Readable, Initialized Data) |
| **`.data`** | `0x0000C000` | `0x0B28` | `0x0000A200` | 1,024 B | `0xC0000040` (Read/Write Data) |
| **`.pdata`** | `0x0000D000` | `0x05C4` | `0x0000A600` | 1,536 B | `0x40000040` (x64 Exception Unwind Data) |
| **`.rsrc`** | `0x0000E000` | `0x81B0` | `0x0000AC00` | 33,280 B | `0x40000040` (Icons, Version Info, Manifest) |
| **`.reloc`** | `0x00017000` | `0x0068` | `0x00012E00` | 512 B | `0x42000040` (Base Relocation Table) |

---

## 3. Imported Core DLLs

From `CapCut_Decoded_EXE/imported_libraries.txt`:

1. **`Qt6Core.dll` & `Qt6Qml.dll`** — Qt 6 graphical framework runtime and QML declarative engine initialization.
2. **`VESafeGuard.dll` & `VEConfig.dll`** — ByteDance Video Engine runtime protection and configuration engine.
3. **`KERNEL32.dll`** — Base Windows operating system API (threads, memory allocation, handles, environment).
4. **`MSVCP140.dll` & `VCRUNTIME140.dll`** — Microsoft Visual C++ 2015-2022 64-bit runtime.
5. **Universal CRT (`api-ms-win-crt-*`)** — Standard C library runtime.

---

## 4. Decoded Files in this Directory

- [pe_headers.json](file:///c:/Users/Usuario/Desktop/msdm/CapCut_Decoded_EXE/pe_headers.json) — Full JSON dump of all PE headers, data directories, and section attributes.
- [imported_libraries.txt](file:///c:/Users/Usuario/Desktop/msdm/CapCut_Decoded_EXE/imported_libraries.txt) — List of all linked dynamic libraries.
- [extracted_strings.txt](file:///c:/Users/Usuario/Desktop/msdm/CapCut_Decoded_EXE/extracted_strings.txt) — 3,111 ASCII and string symbols extracted directly from the binary.
