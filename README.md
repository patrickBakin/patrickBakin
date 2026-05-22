# Patrick Bakin

**Game Developer & Reverse Engineer · Unreal Engine 4/5**

I build native tools, SDKs, and mods for Unreal Engine games. Comfortable working from x64 disassembly up to UE5 Blueprint — pattern scanning, memory hooking, IPC, and gameplay systems are my bread and butter.

Most of my work targets shipped commercial titles, where there's no source access and reliability across game updates matters. That constraint shapes how I write tools: version-resilient signatures, defensive offset resolution, and SDKs that survive engine churn.

---

## Featured Projects

### [UE4-Function-Address-Finder](https://github.com/patrickBakin/UE4-Function-Address-Finder) ⭐ 43
Automates locating `GNames`, `FNamePool`, `GObjects`, `GWorld`, and core engine function addresses across UE4 builds. Uses AOB (array-of-bytes) signature scanning so the same tool works against multiple game versions without re-tuning by hand. Saves hours of manual IDA/Ghidra work per title.

### [ZedfestSDK](https://github.com/patrickBakin/ZedfestSDK)
Generated C++ SDK exposing the full UObject tree of *Zedfest*. Lets mod authors call game functions and read/write properties with type safety instead of raw pointer math.

### [ReadyOrNotModLoader](https://github.com/patrickBakin/ReadyOrNotModLoader)
Loads and spawns Blueprint classes from packaged `.pak` files into a running game instance. Demonstrates pak mounting, asset registry manipulation, and runtime UObject spawning in a shipped UE4 title.

---

## What I Work With

- **Languages:** C++ (primary), Python, Java, C#
- **Engine:** Unreal Engine 4 & 5 — native modding, Blueprint, pak/asset internals
- **Reverse engineering:** x64 disassembly, pattern scanning, hook frameworks (Detours, MinHook), DLL injection
- **Tooling:** Windows native APIs, IPC (TCP, named pipes), msgpack/protobuf, OpenCV, ML (PyTorch / TF for [Chord_Recognition_Python](https://github.com/patrickBakin/Chord_Recognition_Python))

## What I'm Looking For

Gameplay programming, engine tools, or reverse-engineering-adjacent roles — especially anywhere the work involves shipped engines, native code, and squeezing capability out of systems that weren't built to be extended.

## Contact

- 📧 **nsillavich@gmail.com**
- 💬 **Discord:** `potatopie1864`
- 🔗 **GitHub:** [@patrickBakin](https://github.com/patrickBakin)
