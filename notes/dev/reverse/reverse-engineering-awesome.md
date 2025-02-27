---
title: Reverse Engineering Awesome
tags:
  - Awesome
---

# Reverse Engineering Awesome

- [rr-debugger/rr](https://github.com/rr-debugger/rr)
- [radareorg/radare2](https://github.com/radareorg/radare2)
  - CLI
  - [rizinorg/cutter](https://github.com/rizinorg/cutter)
    - GPLv3, C++
- Ghidra
- IDA Pro

```bash
brew install radare2
r2 -v

# https://cutter.re/docs/user-docs/shortcuts.html
brew install --cask cutter # GUI for radare2
```

---

- PLT - Procedure Linkage Table
  - `Sdk::Decrypt(std::string const&, std::string const&, std::string*)`
- GOT - Global Offset Table

## HEX Editor

- [WerWolv/ImHex](https://github.com/WerWolv/ImHex)
  - GPLv2, C++
- [synalysis](https://www.synalysis.net/)
  - macOS

## Assembly RE Tools

- [x64dbg/x64dbg](https://github.com/x64dbg/x64dbg)
  - x64/x32 debugger windows
- [rizinorg/rizin](https://github.com/rizinorg/rizin)
  - UNIX-like, RE framework, command-line toolset
- [radareorg/cutter](https://github.com/radareorg/cutter)
  - reverse engineering platform
  - 基于 rizin
  - Qt C++
- [frida/frida](https://github.com/frida/frida)
  - Dynamic instrumentation toolkit

## 参考

- [USB Reverse Engineering: Down the Rabbit Hole](http://devalias.net/devalias/2018/05/13/usb-reverse-engineering-down-the-rabbit-hole/)
  - [HN](https://news.ycombinator.com/item?id=17164700)
- [Reversing for dummies - x86 assembly and C code](https://0x41.cf/reversing/2021/07/21/reversing-x86-and-c-code-for-beginners.html)
