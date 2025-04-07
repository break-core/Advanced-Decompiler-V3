# Advanced Decompiler V3
This code is a fork of a rewrite of Advanced Decompiler V3.

The actual rewrite code was created by wae (original creator of Advanced Decompiler V3). For exploit support and better studio support, that was created by me.

# What is this?
This is a disassembler, which takes bytecode and tries to transform it into readable instructions. A particularly useful feature of this is that it can predict what opcodes are used for, so you don't have to be a total rocket scientist to understand what's going on here.

# How good it is?
Compared to the previous version of Advanced Decompiler V3 (which had several errors), this version has NEVER failed yet on any bytecode and has been tested on massive Roblox scripts such as the latest version of Criminality's GunScript (which is around 5000+ lines long). If you're a reverse engineer, this will be perfect for you!

# Credits
- w-a-e: Created the original rewrite of Advanced Decompiler V3
- break-core (me): Edited the rewrite to support exploits, better support for Roblox Studio, and Base64 decoding support
- Reselim: Creator of the ultra-fast buffer-based Base64 module used here