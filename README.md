<p align="center">
  <img src="https://img.shields.io/badge/Game-Offsets--SDK--Collection-blue?style=for-the-badge&logo=github" alt="Title Badge"/>
  <br>
  <img src="https://img.shields.io/github/stars/AIN-sch/Game-Offsets-SDK-Collection?style=flat-square&label=Stars&color=yellow" alt="Stars"/>
  <img src="https://img.shields.io/github/last-commit/AIN-sch/Game-Offsets-SDK-Collection?style=flat-square&label=Last%20Update" alt="Last Update"/>
  <img src="https://img.shields.io/badge/topics-game--hacking-blue?style=flat-square" alt="Game Hacking"/>
  <img src="https://img.shields.io/badge/topics-reverse--engineering-blue?style=flat-square" alt="Reverse Engineering"/>
</p>

<h1 align="center">🎮 Game Offsets & SDK Collection</h1>

<p align="center">
  <b>收集各游戏的 SDK、内存基址与偏移量数据</b><br>
  <i>A public collection of game memory dumps, offsets, SDKs and reverse engineering data.</i>
  <br><br>
  不定期更新 · 随缘维护 · 欢迎贡献
</p>

---

## 📋 收录清单

| 目录 | 日期 | 引擎 | 说明 |
|------|------|------|------|
| `CS2-2026.5.5/` | 2026-05-05 | Source 2 | CS2 内存 Dump（cs / hpp / json / rs / zig） |
| `ClimberAnimals-2026.5.6/` | 2026-05-06 | Unity (IL2CPP) | Climber Animals Together Dump |
| `EscapeTheBackrooms-2026.5.7/` | 2026-05-07 | Unreal Engine 4 | EscapeTheBackrooms Dump（CppSDK / Dumpspace / IDAMappings） |

---

## 📁 目录结构说明

每个游戏数据按类型分类存放：

| 目录 | 说明 |
|------|------|
| `cs/` | C# 源码 |
| `hpp/` | C++ 头文件 / Offsets |
| `json/` | JSON 格式数据 |
| `rs/` | Rust 源码 |
| `zig/` | Zig 源码 |
| `dll/` | 虚拟 DLL |
| `CppSDK/` | C++ SDK |
| `Dumpspace/` | 分类 Dump 数据 |
| `IDAMappings/` | IDA 映射文件 |
| `Mappings/` | 引擎映射文件 |

---

## 🧭 这个仓库可以用来做什么

- 快速查阅已知游戏的基址与偏移量
- 作为逆向开发的参考数据
- 对比不同引擎（Source 2 / UE4 / Unity IL2CPP）的内存结构差异
- 学习游戏 Dump 数据的组织方式

---

## ⚠️ 注意事项

- 数据仅供 **学习参考**，请勿用于非法用途
- 随游戏版本更新，部分数据可能 **失效**
- 欢迎提交 Issue 或 PR 补充其他游戏

---

## 💬 交流

有问题想交流，或者单纯对游戏逆向感兴趣？

<p align="center">
  <b>QQ 群：1019998147</b><br>
  拒绝广告，谢绝引战，单纯的技术交流。
</p>

---

<p align="center">
  <sub>⭐ If you find this useful, consider starring the repo — it helps others discover it.</sub>
  <br>
  <sub>Maintained with ❤️ by <a href="https://github.com/AIN-sch">AIN-sch</a></sub>
</p>
