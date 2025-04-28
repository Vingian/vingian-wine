# 🍷 Vingian-Wine

A custom [Wine](https://www.winehq.org/) build designed to run most games out of the box.

---

## ✨ Features

This Wine build comes with everything you need to start gaming immediately:

* Compiled using [LLVM/Clang](https://clang.llvm.org/) and [LTO](https://llvm.org/docs/LinkTimeOptimization.html) for smaller and faster binaries
* [Wine Staging](https://gitlab.winehq.org/wine/wine-staging) and [Wine TKG](https://github.com/Frogging-Family/wine-tkg-git) patches for enhanced functionality
* [Wine Gecko](https://gitlab.winehq.org/wine/wine-gecko) and [Wine Mono](https://gitlab.winehq.org/mono/wine-mono) embedded
* [DXVK](https://github.com/doitsujin/dxvk) and [VKD3D-Proton](https://github.com/HansKristian-Work/vkd3d-proton) built-in for DirectX 8~12 to Vulkan translation
* [DXVK-NVAPI](https://github.com/jp7677/dxvk-nvapi) for NVIDIA features support
* Custom patches for improved compatibility with EAC and nProtect GameGuard anti-cheat systems
* DLSS support configuration made easy

---

## 🚀 Getting Started

👉 [Download the latest release](https://github.com/vingian/vingian-wine/releases)

Extract it anywhere and you're ready to go!

---

## 🕹️ Usage Example

### Star Citizen

#### Installing the game:
```bash
WINEPREFIX="/prefix/path" /path/to/vingian-wine/bin/wine "/installer/path/RSI Launcher-Setup.exe"
```

#### Running the game:
```bash
WINEPREFIX="/prefix/path" /path/to/vingian-wine/bin/wine "c:\\Program Files\\Roberts Space Industries\\RSI Launcher\\RSI Launcher.exe"
```

It's that simple!

---

## 🧩 Custom Patches

You can find most of the custom patches used in this Wine build in [Star Citizen LUG Patches repository](https://github.com/starcitizen-lug/patches).

---

## 🧪 Other Wine Builds That You Should Definitely Try

- [GE-Proton](https://github.com/GloriousEggroll/proton-ge-custom/releases)
- [Kron4ek Wine Builds](https://github.com/Kron4ek/Wine-Builds/releases)
- [Mactan Wine](https://github.com/mactan-sc/mactan-sc-wine/releases)
- [Raw-Wine](https://github.com/starcitizen-lug/raw-wine/releases)

---

## 💭 Final Thoughts

This custom Wine build was originally created for personal use — mainly for myself and a few friends who were looking for better out-of-the-box compatibility with Windows games on Linux.

After seeing how well it performed and how much frustration it saved us during setups, I decided to share it publicly in the hope that it might help others too.

If this build helps you run that one stubborn game, saves you time, or just makes your Linux gaming experience smoother — that's already a win for me. 🎮🐧

For questions or feedback, feel free to reach out on Discord: **Vingian**
