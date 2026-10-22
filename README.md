# Mikes_UEFI_Variety_store

> [English version below](#english) ｜ [跳到英文版](#english)

**Mike 同学的 UEFI 作品集** —— 这是 Mike Wu 在 UEFI 这条路上做出来的东西的**聚合目录**：工具、大模型 Skill、游戏，以及其他一些周边项目，全都在这一页里，**省得各位到处找**。

这个仓库**只有一个 README**，不存任何工具实体——没有源码，没有二进制，也没有那些散在各个角落的下载链接。每个条目都配一张从原仓库取来的典型图片，附一句说明，**点一下就跳到它自己的 GitHub 仓库**去看详情、拿 Release、看文档。

所有条目按大类分组（工具 / Skill / 游戏 / 其他），**每类内部按 star 数从高到低排**。star 数会变，顺序也会跟着变——但你的 star 可以把它顶上去。

> The single landing page for everything Mike Wu has built around UEFI: tools, LLM skills, games and the rest — all in one place, so nobody has to hunt. This repository contains **only this README**: no source code, no binaries, no scattered download links. Every entry shows one representative screenshot taken from its own repository and links straight to that repository.
>
> Items are grouped by category (Tools / Skills / Games / Others) and **sorted by star count, highest first** within each group.

---

## 目录 / Contents

### 🧰 工具 / Tools

<table>
<tr><td align="center" valign="top" width="33%"><a href="#gsetupmod"><img src="assets/gsetupmod.png" width="300" alt="gsetupmod"></a><br><a href="#gsetupmod"><b>gsetupmod</b></a> <sub>★121</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-test-suite"><img src="assets/uefi-test-suite.png" width="300" alt="UEFI_Test_Suite"></a><br><a href="#uefi-test-suite"><b>UEFI_Test_Suite</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#advdisktest"><img src="assets/advdisktest.png" width="300" alt="AdvDiskTest"></a><br><a href="#advdisktest"><b>AdvDiskTest</b></a> <sub>★65</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#advmemtest"><img src="assets/advmemtest.png" width="300" alt="AdvMemTest"></a><br><a href="#advmemtest"><b>AdvMemTest</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#bootdoctor"><img src="assets/bootdoctor.png" width="300" alt="BootDoctor"></a><br><a href="#bootdoctor"><b>BootDoctor</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#pcdig"><img src="assets/pcdig.png" width="300" alt="pcDig"></a><br><a href="#pcdig"><b>pcDig</b></a> <sub>★65</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#gudumpinfo"><img src="assets/gudumpinfo.png" width="300" alt="gudumpinfo"></a><br><a href="#gudumpinfo"><b>gudumpinfo</b></a> <sub>★50</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-lvgl"><img src="assets/uefi-lvgl.png" width="300" alt="UEFI_LVGL"></a><br><a href="#uefi-lvgl"><b>UEFI_LVGL</b></a> <sub>★23</sub></td><td align="center" valign="top" width="33%"><a href="#uefieraser"><img src="assets/uefieraser.png" width="300" alt="UefiEraser"></a><br><a href="#uefieraser"><b>UefiEraser</b></a> <sub>★21</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uwinunlocker"><img src="assets/uwinunlocker.png" width="300" alt="uwinunlocker"></a><br><a href="#uwinunlocker"><b>uwinunlocker</b></a> <sub>★21</sub></td><td align="center" valign="top" width="33%"><a href="#acpicapkg"><img src="assets/acpicapkg.png" width="300" alt="AcpicaPkg"></a><br><a href="#acpicapkg"><b>AcpicaPkg</b></a> <sub>★9</sub></td><td align="center" valign="top" width="33%"><a href="#biosllm"><img src="assets/biosllm.png" width="300" alt="biosllm"></a><br><a href="#biosllm"><b>biosllm</b></a> <sub>★7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#guedit"><img src="assets/guedit.png" width="300" alt="guedit"></a><br><a href="#guedit"><b>guedit</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#mount"><img src="assets/mount.png" width="300" alt="mount"></a><br><a href="#mount"><b>mount</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-nesemu"><img src="assets/uefi-nesemu.png" width="300" alt="UEFI_NesEmu"></a><br><a href="#uefi-nesemu"><b>UEFI_NesEmu</b></a> <sub>★6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uime"><img src="assets/uime.png" width="300" alt="uIME"></a><br><a href="#uime"><b>uIME</b></a> <sub>★5</sub></td><td align="center" valign="top" width="33%"><a href="#gufile"><img src="assets/gufile.png" width="300" alt="gufile"></a><br><a href="#gufile"><b>gufile</b></a> <sub>★2</sub></td><td align="center" valign="top" width="33%"><a href="#rustpaint"><img src="assets/rustpaint.png" width="300" alt="rustpaint"></a><br><a href="#rustpaint"><b>rustpaint</b></a> <sub>★1</sub></td></tr>
</table>


### 🧠 大模型 Skill / Skills

<table>
<tr><td align="center" valign="top" width="33%"><a href="#emulator-uefi-shell-app"><img src="assets/emulator-uefi-shell-app.png" width="300" alt="emulator-uefi-shell-app"></a><br><a href="#emulator-uefi-shell-app"><b>emulator-uefi-shell-app</b></a> <sub>★70</sub></td><td align="center" valign="top" width="33%"><a href="#pdf2md"><img src="assets/pdf2md.png" width="300" alt="pdf2md"></a><br><a href="#pdf2md"><b>pdf2md</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#pdf-watermark-removal"><img src="assets/pdf-watermark-removal.png" width="300" alt="pdf-watermark-removal"></a><br><a href="#pdf-watermark-removal"><b>pdf-watermark-removal</b></a> <sub>★31</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#bios-security-analysis"><img src="assets/bios-security-analysis.png" width="300" alt="bios-security-analysis"></a><br><a href="#bios-security-analysis"><b>bios-security-analysis</b></a> <sub>★17</sub></td><td align="center" valign="top" width="33%"><a href="#nes-reverse-engineering"><img src="assets/nes-reverse-engineering.png" width="300" alt="nes-reverse-engineering"></a><br><a href="#nes-reverse-engineering"><b>nes-reverse-engineering</b></a> <sub>★5</sub></td><td align="center" valign="top" width="33%"><a href="#tech-figures"><img src="assets/tech-figures.png" width="300" alt="tech-figures"></a><br><a href="#tech-figures"><b>tech-figures</b></a> <sub>★4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#rust-in-edk2-uefi-app"><img src="assets/rust-in-edk2-uefi-app.png" width="300" alt="rust-in-edk2-uefi-app"></a><br><a href="#rust-in-edk2-uefi-app"><b>rust-in-edk2-uefi-app</b></a> <sub>★2</sub></td><td></td><td></td></tr>
</table>


### 🎮 游戏 / Games

<table>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-supermario"><img src="assets/uefi-supermario.png" width="300" alt="UEFI_SuperMario"></a><br><a href="#uefi-supermario"><b>UEFI_SuperMario</b></a> <sub>★36</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-contra"><img src="assets/uefi-contra.png" width="300" alt="UEFI_Contra"></a><br><a href="#uefi-contra"><b>UEFI_Contra</b></a> <sub>★27</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-jackal"><img src="assets/uefi-jackal.png" width="300" alt="UEFI_Jackal"></a><br><a href="#uefi-jackal"><b>UEFI_Jackal</b></a> <sub>★16</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-tank"><img src="assets/uefi-tank.png" width="300" alt="UEFI_tank"></a><br><a href="#uefi-tank"><b>UEFI_tank</b></a> <sub>★13</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-battlecity"><img src="assets/uefi-battlecity.png" width="300" alt="UEFI_battlecity"></a><br><a href="#uefi-battlecity"><b>UEFI_battlecity</b></a> <sub>★7</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-goonies"><img src="assets/uefi-goonies.png" width="300" alt="UEFI_Goonies"></a><br><a href="#uefi-goonies"><b>UEFI_Goonies</b></a> <sub>★6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-nesemu"><img src="assets/uefi-nesemu.png" width="300" alt="UEFI_NesEmu"></a><br><a href="#uefi-nesemu"><b>UEFI_NesEmu</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-salamander"><img src="assets/uefi-salamander.png" width="300" alt="UEFI_Salamander"></a><br><a href="#uefi-salamander"><b>UEFI_Salamander</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-snake"><img src="assets/uefi-snake.png" width="300" alt="UEFI_Snake"></a><br><a href="#uefi-snake"><b>UEFI_Snake</b></a> <sub>★6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-supermario-mver"><img src="assets/uefi-supermario-mver.png" width="300" alt="UEFI_SuperMario_MVer"></a><br><a href="#uefi-supermario-mver"><b>UEFI_SuperMario_MVer</b></a> <sub>★5</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-sf3"><img src="assets/uefi-sf3.png" width="300" alt="UEFI_SF3"></a><br><a href="#uefi-sf3"><b>UEFI_SF3</b></a> <sub>★4</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-shmup"><img src="assets/uefi-shmup.png" width="300" alt="UEFI_Shmup"></a><br><a href="#uefi-shmup"><b>UEFI_Shmup</b></a> <sub>★3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-bomberman"><img src="assets/uefi-bomberman.png" width="300" alt="UEFI_bomberman"></a><br><a href="#uefi-bomberman"><b>UEFI_bomberman</b></a> <sub>★2</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-breakout"><img src="assets/uefi-breakout.png" width="300" alt="UEFI_Breakout"></a><br><a href="#uefi-breakout"><b>UEFI_Breakout</b></a> <sub>★1</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-pacman"><img src="assets/uefi-pacman.png" width="300" alt="UEFI_Pacman"></a><br><a href="#uefi-pacman"><b>UEFI_Pacman</b></a> <sub>★1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-tetris"><img src="assets/uefi-tetris.png" width="300" alt="UEFI_Tetris"></a><br><a href="#uefi-tetris"><b>UEFI_Tetris</b></a> <sub>★1</sub></td><td></td><td></td></tr>
</table>


### 📦 其他 / Others

<table>
<tr><td align="center" valign="top" width="33%"><a href="#disasm-goonies"><img src="assets/disasm-goonies.png" width="300" alt="disasm_Goonies"></a><br><a href="#disasm-goonies"><b>disasm_Goonies</b></a> <sub>★1</sub></td><td></td><td></td></tr>
</table>


---

## 详情 / Details

### 🧰 工具 / Tools

<a id="gsetupmod"></a>

#### gsetupmod

**固件设置浏览器** ｜ ★121 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：—

<img src="assets/gsetupmod.png" width="640" alt="gsetupmod">

解析 HII/IFR 重建 BIOS Setup，把被固件藏起来的选项全部摊开给你看。改的是固件里真实存在的那些项，不猜、不试错。

👉 **[进入 gsetupmod 仓库](https://github.com/MikeWuPing/gsetupmod)**

<a id="uefi-test-suite"></a>

#### UEFI_Test_Suite

**UEFI 硬件诊断工具套件** ｜ ★65 ｜ 分类：工具 ｜ 语言：HTML ｜ 许可：个人免费 / 商用授权

<img src="assets/uefi-test-suite.png" width="640" alt="UEFI_Test_Suite">

面向 UEFI 环境的硬件诊断、测试与维修辅助工具二进制发布仓，本仓不含源码，只放二进制、可启动镜像与产品文档。套件里的四件工具（pcDig / BootDoctor / AdvMemTest / AdvDiskTest）在下方已拆散单列，指向同一个仓。

👉 **[进入 UEFI_Test_Suite 仓库](https://github.com/MikeWuPing/UEFI_Test_Suite)**

<a id="advdisktest"></a>

#### AdvDiskTest

**硬盘检测工具** ｜ ★65 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：个人免费 / 商用授权

<img src="assets/advdisktest.png" width="640" alt="AdvDiskTest">

UEFI 原生的硬盘与固态检测：设备识别、健康与磨损双轴判定、PCIe 链路降级六档判定、全盘只读表面扫描与逐区域速度剖面、设备自检、错误日志、容量核验与 HTML 报告导出。测的是盘，也测盘连着的那条链路。

👉 **[进入 AdvDiskTest 仓库](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/AdvDiskTest)** ｜ 📦 随 [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite) 一同发布

<a id="advmemtest"></a>

#### AdvMemTest

**内存压力测试工具** ｜ ★65 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：个人免费 / 商用授权

<img src="assets/advmemtest.png" width="640" alt="AdvMemTest">

对标 Memtest86 全家：33 条真实测试 pattern，四线程模式真实多核调度，自我重定位，动态 DIMM 可视化带（最大 48 槽），平台信息条与计时，HTML 报告自动落盘。专业版把错误指认精确到颗粒级（Socket / Channel / DIMM / Rank / Device 五级坐标）。

👉 **[进入 AdvMemTest 仓库](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/AdvMemTest)** ｜ 📦 随 [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite) 一同发布

<a id="bootdoctor"></a>

#### BootDoctor

**启动诊断修复工具** ｜ ★65 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：个人免费 / 商用授权

<img src="assets/bootdoctor.png" width="640" alt="BootDoctor">

bootrec 与 bcdboot 的图形版：扫描所有分区找 Windows / Linux 安装，四色列出启动链问题，一键修复加自动收敛轮——补 bootmgfw 启动项、重建 ESP、修复 BCD、删除死项、顺序修复。拖拽改序，免责门控与备份先行。

👉 **[进入 BootDoctor 仓库](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/BootDoctor)** ｜ 📦 随 [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite) 一同发布

<a id="pcdig"></a>

#### pcDig

**整机硬件诊断工具** ｜ ★65 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：个人免费 / 商用授权

<img src="assets/pcdig.png" width="640" alt="pcDig">

对标 Dell BIOS 内建 Diagnostics 与 PC-Check：把「机器能不能开机」拆成 21 项可判定的检查，逐项给 OK / WARN / FAIL 结论，扫描条放大镜可视化，左树实时联动，汇总弹窗加 HTML 报告。UEFI Shell 或免 Shell 可启动 ISO 皆可。

👉 **[进入 pcDig 仓库](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/pcDig)** ｜ 📦 随 [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite) 一同发布

<a id="gudumpinfo"></a>

#### gudumpinfo

**图形化系统信息查看器** ｜ ★50 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：NOASSERTION

<img src="assets/gudumpinfo.png" width="640" alt="gudumpinfo">

跑在 UEFI Shell 里的 GUI 系统信息查看器：Handle 中心、协议中心、内存、ACPI、CPUID、MSR、Event-Timer、DEPEX 等 20 类固件底层信息，X64 与 AArch64 都支持。

👉 **[进入 gudumpinfo 仓库](https://github.com/MikeWuPing/gudumpinfo)**

<a id="uefi-lvgl"></a>

#### UEFI_LVGL

**LVGL v9 的 UEFI 移植包** ｜ ★23 ｜ 分类：工具 ｜ 语言：C ｜ 许可：MIT

<img src="assets/uefi-lvgl.png" width="640" alt="UEFI_LVGL">

把 LVGL 图形库搬进 UEFI 固件环境的 EDK2 软件包，自带完整移植层：GOP 显示、键盘、鼠标、节拍时钟与内存管理。本站多个 GUI 工具都建在它之上。

👉 **[进入 UEFI_LVGL 仓库](https://github.com/MikeWuPing/UEFI_LVGL)**

<a id="uefieraser"></a>

#### UefiEraser

**磁盘数据粉碎工具** ｜ ★21 ｜ 分类：工具 ｜ 语言：C ｜ 许可：MIT（Free）/ 专有（Pro）

<img src="assets/uefieraser.png" width="640" alt="UefiEraser">

在操作系统启动之前，对整块物理磁盘、单个分区或分区的空闲空间执行不可恢复的多遍覆写，12 种行业标准算法，末遍回读校验，附安全闸门与 CSV 审计日志。Free 版 MIT 开源，设备级擦除属商业版 Pro。

👉 **[进入 UefiEraser 仓库](https://github.com/MikeWuPing/UefiEraser)**

<a id="uwinunlocker"></a>

#### uwinunlocker

**离线重置 Windows 本地账户密码** ｜ ★21 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：个人免费 / 商用授权

<img src="assets/uwinunlocker.png" width="640" alt="uwinunlocker">

在操作系统起来之前，把 Windows 本地账户的登录密码清掉：不用进 Windows、不用原密码、不联网，也不替换 sethc.exe、不改引导链、不动系统里的任何可执行文件。写前读卷脏标志，写后逐字节回读校验。

👉 **[进入 uwinunlocker 仓库](https://github.com/MikeWuPing/uwinunlocker)**

<a id="acpicapkg"></a>

#### AcpicaPkg

**ACPICA 的 UEFI 封装** ｜ ★9 ｜ 分类：工具 ｜ 语言：C ｜ 许可：MIT

<img src="assets/acpicapkg.png" width="640" alt="AcpicaPkg">

把 ACPICA（UEFI 体系里的 ACPI 解释器）封装成 EDK2 软件包，给 UEFI 开发者用。

👉 **[进入 AcpicaPkg 仓库](https://github.com/MikeWuPing/AcpicaPkg)**

<a id="biosllm"></a>

#### biosllm

**UEFI 固件里的大模型终端** ｜ ★7 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：NOASSERTION

<img src="assets/biosllm.png" width="640" alt="biosllm">

运行在 UEFI 固件里的大模型终端：读硬件、查配置，开机即问，不需要操作系统。Free 版免费授权个人用户使用。

👉 **[进入 biosllm 仓库](https://github.com/MikeWuPing/biosllm)**

<a id="guedit"></a>

#### guedit

**图形化文本编辑器** ｜ ★6 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：—

<img src="assets/guedit.png" width="640" alt="guedit">

跑在 UEFI Shell 里的 GUI 文本编辑器，基于 LVGL 构建。液态玻璃界面，状态栏与快捷键面板齐备。

👉 **[进入 guedit 仓库](https://github.com/MikeWuPing/guedit)**

<a id="mount"></a>

#### mount

**UEFI Shell 挂载工具** ｜ ★6 ｜ 分类：工具 ｜ 语言：C ｜ 许可：NOASSERTION

<img src="assets/mount.png" width="640" alt="mount">

一条 UEFI Shell 命令挂载 ISO、NTFS、ext4、btrfs、XFS 等卷，挂上的 ISO 还能当虚拟块设备用（LoopDisk）。

👉 **[进入 mount 仓库](https://github.com/MikeWuPing/mount)**

<a id="uefi-nesemu"></a>

#### UEFI_NesEmu

**NES 模拟器（UEFI 移植）** ｜ ★6 ｜ 分类：工具、游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-nesemu.png" width="640" alt="UEFI_NesEmu">

纯 C 语言写的 NES 模拟器，从原本基于 SDL3 的版本移植到 UEFI Shell 环境。它既是工具也是游戏——红白机卡带在固件里跑起来了。既列在工具也列在游戏两处。

👉 **[进入 UEFI_NesEmu 仓库](https://github.com/MikeWuPing/UEFI_NesEmu)**

<a id="uime"></a>

#### uIME

**UEFI Shell 中文输入法** ｜ ★5 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：NOASSERTION

<img src="assets/uime.png" width="640" alt="uIME">

UEFI 下的中文输入法：候选窗、双拼、简拼，浮在宿主窗口之上。中文界面里的最后一块拼图。

👉 **[进入 uIME 仓库](https://github.com/MikeWuPing/uIME)**

<a id="gufile"></a>

#### gufile

**图形化文件管理器** ｜ ★2 ｜ 分类：工具 ｜ 语言：二进制发布（无源码） ｜ 许可：—

<img src="assets/gufile.png" width="640" alt="gufile">

UEFI Shell 下的 GUI 文件管理器，Explorer 式界面：目录树、复制粘贴、新建文件夹一应俱全。

👉 **[进入 gufile 仓库](https://github.com/MikeWuPing/gufile)**

<a id="rustpaint"></a>

#### rustpaint

**Rust 写的 UEFI 画板** ｜ ★1 ｜ 分类：工具 ｜ 语言：Rust ｜ 许可：MIT

<img src="assets/rustpaint.png" width="640" alt="rustpaint">

一个用 Rust 写的小画板 UEFI 应用，LVGL 负责渲染。Rust 逻辑 + EDK2 链接 + LVGL 出图，工具栏、调色板、状态栏俱全。

👉 **[进入 rustpaint 仓库](https://github.com/MikeWuPing/rustpaint)**


### 🧠 大模型 Skill / Skills

<a id="emulator-uefi-shell-app"></a>

#### emulator-uefi-shell-app

**UEFI Shell 应用开发技能** ｜ ★70 ｜ 分类：Skill ｜ 语言：PowerShell ｜ 许可：—

<img src="assets/emulator-uefi-shell-app.png" width="640" alt="emulator-uefi-shell-app">

为 Claude Code 提供的 UEFI Shell 应用程序开发完整知识库：从环境搭建到调试部署的全流程，附带可复用的构建与 QEMU 测试脚本模板。

👉 **[进入 emulator-uefi-shell-app 仓库](https://github.com/MikeWuPing/emulator-uefi-shell-app)**

<a id="pdf2md"></a>

#### pdf2md

**PDF 转 Markdown** ｜ ★65 ｜ 分类：Skill ｜ 语言：Python ｜ 许可：—

<img src="assets/pdf2md.png" width="640" alt="pdf2md">

把 PDF 技术文档（规格书、数据手册、参考手册）批量转换成高质量 Markdown：保留表格结构、提取嵌入图片、自动清除水印。

👉 **[进入 pdf2md 仓库](https://github.com/MikeWuPing/pdf2md)**

<a id="pdf-watermark-removal"></a>

#### pdf-watermark-removal

**PDF 水印移除技能** ｜ ★31 ｜ 分类：Skill ｜ 语言：Markdown Skill ｜ 许可：—

<img src="assets/pdf-watermark-removal.png" width="640" alt="pdf-watermark-removal">

给 Claude Code 与 OpenClaw 用的技能：通过分析 PDF 内部结构识别并移除水印，同时保持正常内容完整。

👉 **[进入 pdf-watermark-removal 仓库](https://github.com/MikeWuPing/pdf-watermark-removal)**

<a id="bios-security-analysis"></a>

#### bios-security-analysis

**BIOS 固件安全分析技能** ｜ ★17 ｜ 分类：Skill ｜ 语言：Python ｜ 许可：MIT

<img src="assets/bios-security-analysis.png" width="640" alt="bios-security-analysis">

为 Claude Code 定制的 UEFI / BIOS 固件安全漏洞分析技能：固件镜像解析、深度解压、微码提取、证书审计，直到最终报告输出。

👉 **[进入 bios-security-analysis 仓库](https://github.com/MikeWuPing/bios-security-analysis)**

<a id="nes-reverse-engineering"></a>

#### nes-reverse-engineering

**NES ROM 逆向与忠实重建技能** ｜ ★5 ｜ 分类：Skill ｜ 语言：Python ｜ 许可：MIT

<img src="assets/nes-reverse-engineering.png" width="640" alt="nes-reverse-engineering">

平台无关的方法论：把 NES / Famicom ROM 逆向成忠实的复刻实现，附深度参考与零依赖的提取模板。本站多个 UEFI 游戏就是照这条路做的。

👉 **[进入 nes-reverse-engineering 仓库](https://github.com/MikeWuPing/nes-reverse-engineering)**

<a id="tech-figures"></a>

#### tech-figures

**技术文章配图技能** ｜ ★4 ｜ 分类：Skill ｜ 语言：Python ｜ 许可：MIT

<img src="assets/tech-figures.png" width="640" alt="tech-figures">

给技术文章配图的 skill：把内容变成风格统一的示意图、流程图与结构图。

👉 **[进入 tech-figures 仓库](https://github.com/MikeWuPing/tech-figures)**

<a id="rust-in-edk2-uefi-app"></a>

#### rust-in-edk2-uefi-app

**Rust 写 UEFI 应用技能** ｜ ★2 ｜ 分类：Skill ｜ 语言：Python ｜ 许可：MIT

<img src="assets/rust-in-edk2-uefi-app.png" width="640" alt="rust-in-edk2-uefi-app">

用 Rust（cargo staticlib）写业务逻辑、由 EDK2 链接、LVGL 渲染的 UEFI 应用开发技能——连同那些会静默失败的坑一起写清楚了。

👉 **[进入 rust-in-edk2-uefi-app 仓库](https://github.com/MikeWuPing/rust-in-edk2-uefi-app)**


### 🎮 游戏 / Games

<a id="uefi-supermario"></a>

#### UEFI_SuperMario

**超级马力欧兄弟（UEFI 移植）** ｜ ★36 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-supermario.png" width="640" alt="UEFI_SuperMario">

把红白机《超级马力欧兄弟》移植到 UEFI Shell：GOP 图形输出，纯软件渲染，无音频依赖。QEMU + OVMF 或真机 UEFI Shell 下都能跑。

👉 **[进入 UEFI_SuperMario 仓库](https://github.com/MikeWuPing/UEFI_SuperMario)**

<a id="uefi-contra"></a>

#### UEFI_Contra

**魂斗罗（UEFI 移植）** ｜ ★27 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-contra.png" width="640" alt="UEFI_Contra">

把红白机经典《魂斗罗》移植到 UEFI Shell 的技术实验项目：以 UEFI 应用程序（.efi）直接运行，GOP 渲染画面，无需操作系统，仅依赖 UEFI 固件。

👉 **[进入 UEFI_Contra 仓库](https://github.com/MikeWuPing/UEFI_Contra)**

<a id="uefi-jackal"></a>

#### UEFI_Jackal

**赤色要塞（UEFI 复刻）** ｜ ★16 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-jackal.png" width="640" alt="UEFI_Jackal">

不模拟 NES 硬件，而是把原游戏的 6502 反汇编逐行翻译成平台无关的 C 核心，再以 UEFI GOP 输出图形、UEFI 服务负责输入与定时，在 QEMU 或真实 UEFI 环境中原生运行。

👉 **[进入 UEFI_Jackal 仓库](https://github.com/MikeWuPing/UEFI_Jackal)**

<a id="uefi-tank"></a>

#### UEFI_tank

**坦克大战（1990 经典版）** ｜ ★13 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-tank.png" width="640" alt="UEFI_tank">

UEFI Shell 下的俯视角固定地图坦克射击游戏，复刻 1990 年红白机经典《坦克大战》的核心玩法。

👉 **[进入 UEFI_tank 仓库](https://github.com/MikeWuPing/UEFI_tank)**

<a id="uefi-battlecity"></a>

#### UEFI_battlecity

**FC 坦克大战（UEFI 移植）** ｜ ★7 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-battlecity.png" width="640" alt="UEFI_battlecity">

经典 FC《坦克大战》移植到 UEFI Shell：固件启动后直接在 UEFI Shell 中执行，图形走 GOP，键盘由 Simple Text Input Protocol 驱动，不需要任何操作系统。

👉 **[进入 UEFI_battlecity 仓库](https://github.com/MikeWuPing/UEFI_battlecity)**

<a id="uefi-goonies"></a>

#### UEFI_Goonies

**七宝奇谋（UEFI 复刻）** ｜ ★6 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：NOASSERTION

<img src="assets/uefi-goonies.png" width="640" alt="UEFI_Goonies">

在 UEFI Shell 里复刻 Konami 1986 年的《七宝奇谋》：沿用与赤色要塞相同的路子——6502 反汇编翻译成 C 核心，GOP 出图。

👉 **[进入 UEFI_Goonies 仓库](https://github.com/MikeWuPing/UEFI_Goonies)**

<a id="uefi-nesemu"></a>

#### UEFI_NesEmu

**NES 模拟器（UEFI 移植）** ｜ ★6 ｜ 分类：工具、游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-nesemu.png" width="640" alt="UEFI_NesEmu">

纯 C 语言写的 NES 模拟器，从原本基于 SDL3 的版本移植到 UEFI Shell 环境。它既是工具也是游戏——红白机卡带在固件里跑起来了。既列在工具也列在游戏两处。

👉 **[进入 UEFI_NesEmu 仓库](https://github.com/MikeWuPing/UEFI_NesEmu)**

<a id="uefi-salamander"></a>

#### UEFI_Salamander

**沙罗曼蛇（UEFI 复刻）** ｜ ★6 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-salamander.png" width="640" alt="UEFI_Salamander">

Konami 1986 年的《沙罗曼蛇》（Salamander / Life Force）在 UEFI Shell 下的复刻：6502 反汇编翻译为平台无关的 C 核心，GOP 图形，QEMU / OVMF 验证。

👉 **[进入 UEFI_Salamander 仓库](https://github.com/MikeWuPing/UEFI_Salamander)**

<a id="uefi-snake"></a>

#### UEFI_Snake

**贪吃蛇** ｜ ★6 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-snake.png" width="640" alt="UEFI_Snake">

跑在 UEFI Shell 里的贪吃蛇。EDK2 平台，UEFI 2.7+，x64。

👉 **[进入 UEFI_Snake 仓库](https://github.com/MikeWuPing/UEFI_Snake)**

<a id="uefi-supermario-mver"></a>

#### UEFI_SuperMario_MVer

**超级马力欧兄弟（魔改移植版）** ｜ ★5 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-supermario-mver.png" width="640" alt="UEFI_SuperMario_MVer">

NES《超级马力欧兄弟》的魔改移植版：基于静态 6502 反编译技术以纯 C 实现，GOP 协议输出图形，无需任何操作系统，QEMU 虚拟机或真实硬件上直接启动。

👉 **[进入 UEFI_SuperMario_MVer 仓库](https://github.com/MikeWuPing/UEFI_SuperMario_MVer)**

<a id="uefi-sf3"></a>

#### UEFI_SF3

**街头霸王 III（NES 版，UEFI 复刻）** ｜ ★4 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-sf3.png" width="640" alt="UEFI_SF3">

把街机上的《街头霸王 III》（9 Fighter）在红白机上的 6502 汇编忠实翻译为 C 语言，以 UEFI Shell 应用程序的形式重新实现。

👉 **[进入 UEFI_SF3 仓库](https://github.com/MikeWuPing/UEFI_SF3)**

<a id="uefi-shmup"></a>

#### UEFI_Shmup

**太空战机（纵版射击）** ｜ ★3 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-shmup.png" width="640" alt="UEFI_Shmup">

经典纵版射击游戏，完全运行在 UEFI Shell 环境中。

👉 **[进入 UEFI_Shmup 仓库](https://github.com/MikeWuPing/UEFI_Shmup)**

<a id="uefi-bomberman"></a>

#### UEFI_bomberman

**Bomberman** ｜ ★2 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-bomberman.png" width="640" alt="UEFI_bomberman">

经典 Bomberman 在 UEFI Shell 下的实现。

👉 **[进入 UEFI_bomberman 仓库](https://github.com/MikeWuPing/UEFI_bomberman)**

<a id="uefi-breakout"></a>

#### UEFI_Breakout

**打砖块** ｜ ★1 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-breakout.png" width="640" alt="UEFI_Breakout">

UEFI Shell 下的打砖块。

👉 **[进入 UEFI_Breakout 仓库](https://github.com/MikeWuPing/UEFI_Breakout)**

<a id="uefi-pacman"></a>

#### UEFI_Pacman

**吃豆人** ｜ ★1 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-pacman.png" width="640" alt="UEFI_Pacman">

UEFI Shell 下的吃豆人游戏。

👉 **[进入 UEFI_Pacman 仓库](https://github.com/MikeWuPing/UEFI_Pacman)**

<a id="uefi-tetris"></a>

#### UEFI_Tetris

**俄罗斯方块** ｜ ★1 ｜ 分类：游戏 ｜ 语言：C ｜ 许可：—

<img src="assets/uefi-tetris.png" width="640" alt="UEFI_Tetris">

UEFI Shell 下的俄罗斯方块。

👉 **[进入 UEFI_Tetris 仓库](https://github.com/MikeWuPing/UEFI_Tetris)**


### 📦 其他 / Others

<a id="disasm-goonies"></a>

#### disasm_Goonies

**《七宝奇谋》全 ROM 反汇编工程** ｜ ★1 ｜ 分类：其他 ｜ 语言：Assembly ｜ 许可：—

<img src="assets/disasm-goonies.png" width="640" alt="disasm_Goonies">

《七宝奇谋》（Konami 1986，日版编号 RC809）红白机 ROM 的完整反汇编工程——UEFI 复刻版《七宝奇谋》的底稿就在这里。

👉 **[进入 disasm_Goonies 仓库](https://github.com/MikeWuPing/disasm_Goonies)**


---

## 关于本仓库 / About This Repository

**这个仓是什么** —— Mike Wu 围绕 UEFI / 固件这一路做出来的全部公开作品的**索引页**。工具、Skill、游戏、其他，各归各类，都在这里列全，方便一次性找到。

**这个仓不是什么** —— 它不含任何工具的实体。源码在各自的仓库，二进制在各自的 Releases，本仓只有一张图片和一段说明，把你送到对的地方去。

**条目从哪来** —— 全部是 MikeWuPing 名下的**公开仓库**。私有仓库不在此列。`UEFI_Test_Suite`（UEFI 硬件诊断工具套件）里的四个工具已被拆散成独立条目，分别放在工具类里的对应位置，但**指向的仍是同一个仓库**——因为它们的发布实体就在那儿。

**排序规则** —— 同一大类内按 star 数从高到低。套件内子工具（pcDig / BootDoctor / AdvMemTest / AdvDiskTest）共用宿主仓库 `UEFI_Test_Suite` 的 star 数。

**图片** —— 每张图都取自对应仓库自己的文档或演示素材，仅作示意。

**许可** —— 各项目各自适用自己的许可，详见各自仓库。`UEFI_Test_Suite` 套件内的工具为「个人用户免费使用；商业用途需联系作者授权」。

> **What this is** — the index page for everything Mike Wu has built publicly around UEFI / firmware: tools, LLM skills, games and the rest, all listed in one place.
>
> **What this is not** — it holds no tool artifacts. Source lives in each project's own repository, binaries live in each project's Releases; this page only shows one screenshot and a short paragraph that sends you to the right place.
>
> **Where the entries come from** — all of them are public repositories under MikeWuPing. Private repositories are not indexed. The four tools living inside `UEFI_Test_Suite` have been broken out into individual entries in the Tools section, but they still point to that same repository, because that is where their release artifacts actually are.
>
> **Ordering** — by star count, highest first, within each category. The suite's child tools (pcDig / BootDoctor / AdvMemTest / AdvDiskTest) share the host repository's star count.

---

# English

<a id="english"></a>

**Mike's UEFI variety store** — a single landing page for everything Mike Wu has built around UEFI: tools, large-model skills, games and a few other things, gathered in one place so nobody has to hunt for them.

This repository ships **one README and nothing else** — no source code, no binaries, no scattered download links. Every entry carries one representative screenshot taken from the project's own repository, a short description, and a link straight to that repository.

Entries are grouped into four categories (Tools / Skills / Games / Others) and **sorted by star count, highest first** within each category.

> [中文版](#mikes_uefi_variety_store) ｜ Back to the Chinese version at the top of this page

## Contents

### 🧰 Tools

<table>
<tr><td align="center" valign="top" width="33%"><a href="#gsetupmod-en"><img src="assets/gsetupmod.png" width="300" alt="gsetupmod"></a><br><a href="#gsetupmod-en"><b>gsetupmod</b></a> <sub>★121</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-test-suite-en"><img src="assets/uefi-test-suite.png" width="300" alt="UEFI_Test_Suite"></a><br><a href="#uefi-test-suite-en"><b>UEFI_Test_Suite</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#advdisktest-en"><img src="assets/advdisktest.png" width="300" alt="AdvDiskTest"></a><br><a href="#advdisktest-en"><b>AdvDiskTest</b></a> <sub>★65</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#advmemtest-en"><img src="assets/advmemtest.png" width="300" alt="AdvMemTest"></a><br><a href="#advmemtest-en"><b>AdvMemTest</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#bootdoctor-en"><img src="assets/bootdoctor.png" width="300" alt="BootDoctor"></a><br><a href="#bootdoctor-en"><b>BootDoctor</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#pcdig-en"><img src="assets/pcdig.png" width="300" alt="pcDig"></a><br><a href="#pcdig-en"><b>pcDig</b></a> <sub>★65</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#gudumpinfo-en"><img src="assets/gudumpinfo.png" width="300" alt="gudumpinfo"></a><br><a href="#gudumpinfo-en"><b>gudumpinfo</b></a> <sub>★50</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-lvgl-en"><img src="assets/uefi-lvgl.png" width="300" alt="UEFI_LVGL"></a><br><a href="#uefi-lvgl-en"><b>UEFI_LVGL</b></a> <sub>★23</sub></td><td align="center" valign="top" width="33%"><a href="#uefieraser-en"><img src="assets/uefieraser.png" width="300" alt="UefiEraser"></a><br><a href="#uefieraser-en"><b>UefiEraser</b></a> <sub>★21</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uwinunlocker-en"><img src="assets/uwinunlocker.png" width="300" alt="uwinunlocker"></a><br><a href="#uwinunlocker-en"><b>uwinunlocker</b></a> <sub>★21</sub></td><td align="center" valign="top" width="33%"><a href="#acpicapkg-en"><img src="assets/acpicapkg.png" width="300" alt="AcpicaPkg"></a><br><a href="#acpicapkg-en"><b>AcpicaPkg</b></a> <sub>★9</sub></td><td align="center" valign="top" width="33%"><a href="#biosllm-en"><img src="assets/biosllm.png" width="300" alt="biosllm"></a><br><a href="#biosllm-en"><b>biosllm</b></a> <sub>★7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#guedit-en"><img src="assets/guedit.png" width="300" alt="guedit"></a><br><a href="#guedit-en"><b>guedit</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#mount-en"><img src="assets/mount.png" width="300" alt="mount"></a><br><a href="#mount-en"><b>mount</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-nesemu-en"><img src="assets/uefi-nesemu.png" width="300" alt="UEFI_NesEmu"></a><br><a href="#uefi-nesemu-en"><b>UEFI_NesEmu</b></a> <sub>★6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uime-en"><img src="assets/uime.png" width="300" alt="uIME"></a><br><a href="#uime-en"><b>uIME</b></a> <sub>★5</sub></td><td align="center" valign="top" width="33%"><a href="#gufile-en"><img src="assets/gufile.png" width="300" alt="gufile"></a><br><a href="#gufile-en"><b>gufile</b></a> <sub>★2</sub></td><td align="center" valign="top" width="33%"><a href="#rustpaint-en"><img src="assets/rustpaint.png" width="300" alt="rustpaint"></a><br><a href="#rustpaint-en"><b>rustpaint</b></a> <sub>★1</sub></td></tr>
</table>


### 🧠 Skills

<table>
<tr><td align="center" valign="top" width="33%"><a href="#emulator-uefi-shell-app-en"><img src="assets/emulator-uefi-shell-app.png" width="300" alt="emulator-uefi-shell-app"></a><br><a href="#emulator-uefi-shell-app-en"><b>emulator-uefi-shell-app</b></a> <sub>★70</sub></td><td align="center" valign="top" width="33%"><a href="#pdf2md-en"><img src="assets/pdf2md.png" width="300" alt="pdf2md"></a><br><a href="#pdf2md-en"><b>pdf2md</b></a> <sub>★65</sub></td><td align="center" valign="top" width="33%"><a href="#pdf-watermark-removal-en"><img src="assets/pdf-watermark-removal.png" width="300" alt="pdf-watermark-removal"></a><br><a href="#pdf-watermark-removal-en"><b>pdf-watermark-removal</b></a> <sub>★31</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#bios-security-analysis-en"><img src="assets/bios-security-analysis.png" width="300" alt="bios-security-analysis"></a><br><a href="#bios-security-analysis-en"><b>bios-security-analysis</b></a> <sub>★17</sub></td><td align="center" valign="top" width="33%"><a href="#nes-reverse-engineering-en"><img src="assets/nes-reverse-engineering.png" width="300" alt="nes-reverse-engineering"></a><br><a href="#nes-reverse-engineering-en"><b>nes-reverse-engineering</b></a> <sub>★5</sub></td><td align="center" valign="top" width="33%"><a href="#tech-figures-en"><img src="assets/tech-figures.png" width="300" alt="tech-figures"></a><br><a href="#tech-figures-en"><b>tech-figures</b></a> <sub>★4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#rust-in-edk2-uefi-app-en"><img src="assets/rust-in-edk2-uefi-app.png" width="300" alt="rust-in-edk2-uefi-app"></a><br><a href="#rust-in-edk2-uefi-app-en"><b>rust-in-edk2-uefi-app</b></a> <sub>★2</sub></td><td></td><td></td></tr>
</table>


### 🎮 Games

<table>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-supermario-en"><img src="assets/uefi-supermario.png" width="300" alt="UEFI_SuperMario"></a><br><a href="#uefi-supermario-en"><b>UEFI_SuperMario</b></a> <sub>★36</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-contra-en"><img src="assets/uefi-contra.png" width="300" alt="UEFI_Contra"></a><br><a href="#uefi-contra-en"><b>UEFI_Contra</b></a> <sub>★27</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-jackal-en"><img src="assets/uefi-jackal.png" width="300" alt="UEFI_Jackal"></a><br><a href="#uefi-jackal-en"><b>UEFI_Jackal</b></a> <sub>★16</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-tank-en"><img src="assets/uefi-tank.png" width="300" alt="UEFI_tank"></a><br><a href="#uefi-tank-en"><b>UEFI_tank</b></a> <sub>★13</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-battlecity-en"><img src="assets/uefi-battlecity.png" width="300" alt="UEFI_battlecity"></a><br><a href="#uefi-battlecity-en"><b>UEFI_battlecity</b></a> <sub>★7</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-goonies-en"><img src="assets/uefi-goonies.png" width="300" alt="UEFI_Goonies"></a><br><a href="#uefi-goonies-en"><b>UEFI_Goonies</b></a> <sub>★6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-nesemu-en"><img src="assets/uefi-nesemu.png" width="300" alt="UEFI_NesEmu"></a><br><a href="#uefi-nesemu-en"><b>UEFI_NesEmu</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-salamander-en"><img src="assets/uefi-salamander.png" width="300" alt="UEFI_Salamander"></a><br><a href="#uefi-salamander-en"><b>UEFI_Salamander</b></a> <sub>★6</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-snake-en"><img src="assets/uefi-snake.png" width="300" alt="UEFI_Snake"></a><br><a href="#uefi-snake-en"><b>UEFI_Snake</b></a> <sub>★6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-supermario-mver-en"><img src="assets/uefi-supermario-mver.png" width="300" alt="UEFI_SuperMario_MVer"></a><br><a href="#uefi-supermario-mver-en"><b>UEFI_SuperMario_MVer</b></a> <sub>★5</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-sf3-en"><img src="assets/uefi-sf3.png" width="300" alt="UEFI_SF3"></a><br><a href="#uefi-sf3-en"><b>UEFI_SF3</b></a> <sub>★4</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-shmup-en"><img src="assets/uefi-shmup.png" width="300" alt="UEFI_Shmup"></a><br><a href="#uefi-shmup-en"><b>UEFI_Shmup</b></a> <sub>★3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-bomberman-en"><img src="assets/uefi-bomberman.png" width="300" alt="UEFI_bomberman"></a><br><a href="#uefi-bomberman-en"><b>UEFI_bomberman</b></a> <sub>★2</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-breakout-en"><img src="assets/uefi-breakout.png" width="300" alt="UEFI_Breakout"></a><br><a href="#uefi-breakout-en"><b>UEFI_Breakout</b></a> <sub>★1</sub></td><td align="center" valign="top" width="33%"><a href="#uefi-pacman-en"><img src="assets/uefi-pacman.png" width="300" alt="UEFI_Pacman"></a><br><a href="#uefi-pacman-en"><b>UEFI_Pacman</b></a> <sub>★1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="#uefi-tetris-en"><img src="assets/uefi-tetris.png" width="300" alt="UEFI_Tetris"></a><br><a href="#uefi-tetris-en"><b>UEFI_Tetris</b></a> <sub>★1</sub></td><td></td><td></td></tr>
</table>


### 📦 Others

<table>
<tr><td align="center" valign="top" width="33%"><a href="#disasm-goonies-en"><img src="assets/disasm-goonies.png" width="300" alt="disasm_Goonies"></a><br><a href="#disasm-goonies-en"><b>disasm_Goonies</b></a> <sub>★1</sub></td><td></td><td></td></tr>
</table>


---

## Details

### 🧰 Tools

<a id="gsetupmod-en"></a>

#### gsetupmod

**Firmware Setup Browser** ｜ ★121 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: —

<img src="assets/gsetupmod.png" width="640" alt="gsetupmod">

Parses HII/IFR to rebuild the BIOS Setup screen and exposes the options the firmware chose to hide. It changes options that really exist in the firmware — no guessing, no trial and error.

👉 **[Open the gsetupmod repository](https://github.com/MikeWuPing/gsetupmod)**

<a id="uefi-test-suite-en"></a>

#### UEFI_Test_Suite

**UEFI Hardware Diagnostics Suite** ｜ ★65 ｜ Category: Tool ｜ Language: HTML ｜ License: 个人免费 / 商用授权

<img src="assets/uefi-test-suite.png" width="640" alt="UEFI_Test_Suite">

The binary release repository for UEFI hardware diagnostics, testing and repair-assist tools. No source code here — only binaries, bootable images and documentation. The four tools inside (pcDig / BootDoctor / AdvMemTest / AdvDiskTest) are broken out as individual entries below and all point back to this same repository.

👉 **[Open the UEFI_Test_Suite repository](https://github.com/MikeWuPing/UEFI_Test_Suite)**

<a id="advdisktest-en"></a>

#### AdvDiskTest

**Disk Health Detection Tool** ｜ ★65 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: 个人免费 / 商用授权

<img src="assets/advdisktest.png" width="640" alt="AdvDiskTest">

Native UEFI disk and SSD detection: device identification, two-axis health and wear assessment, six-tier PCIe link degradation classification, a read-only full-disk surface scan with a per-region speed profile, device self-test, error logs, capacity verification and HTML report export. It measures the drive and the link it hangs on.

👉 **[Open the AdvDiskTest repository](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/AdvDiskTest)** ｜ 📦 Released together with [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite)

<a id="advmemtest-en"></a>

#### AdvMemTest

**Memory Stress Test Tool** ｜ ★65 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: 个人免费 / 商用授权

<img src="assets/advmemtest.png" width="640" alt="AdvMemTest">

Memtest86 family style: 33 real test patterns, four multi-core modes with genuine scheduling, self-relocation, a dynamic DIMM strip (up to 48 slots), a platform info bar with elapsed time and an auto-generated HTML report. The Pro edition pinpoints failures at chip level through five-axis coordinates (Socket / Channel / DIMM / Rank / Device).

👉 **[Open the AdvMemTest repository](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/AdvMemTest)** ｜ 📦 Released together with [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite)

<a id="bootdoctor-en"></a>

#### BootDoctor

**Boot Diagnosis & Repair Tool** ｜ ★65 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: 个人免费 / 商用授权

<img src="assets/bootdoctor.png" width="640" alt="BootDoctor">

The graphical counterpart of bootrec + bcdboot: scans every partition for Windows / Linux installations, lists boot-chain findings in four colors, and repairs with one click plus automatic convergence rounds — register a missing bootmgfw entry, rebuild the ESP, rebuild the BCD, delete dead entries, fix ordering. Drag to reorder, with a disclaimer gate and backup-first behavior.

👉 **[Open the BootDoctor repository](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/BootDoctor)** ｜ 📦 Released together with [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite)

<a id="pcdig-en"></a>

#### pcDig

**Whole-Machine Hardware Diagnostics** ｜ ★65 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: 个人免费 / 商用授权

<img src="assets/pcdig.png" width="640" alt="pcDig">

Dell built-in Diagnostics / PC-Check style: splits “can this machine boot” into 21 decidable checks, each returning OK / WARN / FAIL, with scanbar magnifier visualization, a real-time left tree, a completion summary dialog and an HTML report. Runs in the UEFI Shell or from a shell-free bootable ISO.

👉 **[Open the pcDig repository](https://github.com/MikeWuPing/UEFI_Test_Suite/tree/main/pcDig)** ｜ 📦 Released together with [UEFI_Test_Suite](https://github.com/MikeWuPing/UEFI_Test_Suite)

<a id="gudumpinfo-en"></a>

#### gudumpinfo

**Graphic UEFI System Info Viewer** ｜ ★50 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: NOASSERTION

<img src="assets/gudumpinfo.png" width="640" alt="gudumpinfo">

A GUI system-information viewer that runs directly in the UEFI Shell: handle center, protocol center, memory, ACPI, CPUID, MSR, event timer, DEPEX and 20 categories of low-level firmware data. X64 and AArch64 both supported.

👉 **[Open the gudumpinfo repository](https://github.com/MikeWuPing/gudumpinfo)**

<a id="uefi-lvgl-en"></a>

#### UEFI_LVGL

**LVGL v9 for UEFI** ｜ ★23 ｜ Category: Tool ｜ Language: C ｜ License: MIT

<img src="assets/uefi-lvgl.png" width="640" alt="UEFI_LVGL">

An EDK2 package that brings the LVGL graphics library into the firmware environment, complete with a full UEFI port layer: GOP display, keyboard, mouse, tick clock and memory management. Several GUI tools in this collection are built on top of it.

👉 **[Open the UEFI_LVGL repository](https://github.com/MikeWuPing/UEFI_LVGL)**

<a id="uefieraser-en"></a>

#### UefiEraser

**Disk Data Shredder** ｜ ★21 ｜ Category: Tool ｜ Language: C ｜ License: MIT（Free）/ 专有（Pro）

<img src="assets/uefieraser.png" width="640" alt="UefiEraser">

Before any operating system boots, overwrites a whole physical disk, a single partition or a volume's free space irreversibly — 12 industry-standard algorithms, optional last-pass read-back verification, safety gates and a CSV audit log. The Free edition is MIT open source; device-level erase belongs to the commercial Pro edition.

👉 **[Open the UefiEraser repository](https://github.com/MikeWuPing/UefiEraser)**

<a id="uwinunlocker-en"></a>

#### uwinunlocker

**Offline Windows Local Account Password Reset** ｜ ★21 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: 个人免费 / 商用授权

<img src="assets/uwinunlocker.png" width="640" alt="uwinunlocker">

Clears a Windows local account password before the operating system boots: no Windows, no old password, no network — and it never replaces sethc.exe, never touches the boot chain, never modifies any system executable. It reads the volume dirty flag before writing and byte-compares the file back afterwards.

👉 **[Open the uwinunlocker repository](https://github.com/MikeWuPing/uwinunlocker)**

<a id="acpicapkg-en"></a>

#### AcpicaPkg

**ACPICA UEFI Wrapper** ｜ ★9 ｜ Category: Tool ｜ Language: C ｜ License: MIT

<img src="assets/acpicapkg.png" width="640" alt="AcpicaPkg">

Wraps ACPICA — the ACPI interpreter of the UEFI world — as an EDK2 package for UEFI developers.

👉 **[Open the AcpicaPkg repository](https://github.com/MikeWuPing/AcpicaPkg)**

<a id="biosllm-en"></a>

#### biosllm

**LLM Terminal Inside UEFI Firmware** ｜ ★7 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: NOASSERTION

<img src="assets/biosllm.png" width="640" alt="biosllm">

A large-model terminal running inside UEFI firmware: read the hardware, query the configuration, ask right after boot — no operating system involved. The Free edition is licensed free of charge for personal users.

👉 **[Open the biosllm repository](https://github.com/MikeWuPing/biosllm)**

<a id="guedit-en"></a>

#### guedit

**Graphic UEFI Text Editor** ｜ ★6 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: —

<img src="assets/guedit.png" width="640" alt="guedit">

A GUI text editor running in the UEFI Shell, built on LVGL — liquid-glass styling, a status bar and a shortcut panel.

👉 **[Open the guedit repository](https://github.com/MikeWuPing/guedit)**

<a id="mount-en"></a>

#### mount

**UEFI Shell Mount Command** ｜ ★6 ｜ Category: Tool ｜ Language: C ｜ License: NOASSERTION

<img src="assets/mount.png" width="640" alt="mount">

A single UEFI Shell command that mounts ISO, NTFS, ext4, btrfs and XFS volumes — and a mounted ISO can then be used as a virtual block device via LoopDisk.

👉 **[Open the mount repository](https://github.com/MikeWuPing/mount)**

<a id="uefi-nesemu-en"></a>

#### UEFI_NesEmu

**NES Emulator (UEFI Port)** ｜ ★6 ｜ Category: Tool, Game ｜ Language: C ｜ License: —

<img src="assets/uefi-nesemu.png" width="640" alt="UEFI_NesEmu">

A pure-C NES emulator originally built on SDL3, ported to the UEFI Shell environment. It is both a tool and a game — the cartridge now runs inside the firmware. Listed under tools and under games.

👉 **[Open the UEFI_NesEmu repository](https://github.com/MikeWuPing/UEFI_NesEmu)**

<a id="uime-en"></a>

#### uIME

**Chinese IME for UEFI Shell** ｜ ★5 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: NOASSERTION

<img src="assets/uime.png" width="640" alt="uIME">

A Chinese input method for UEFI: candidate window, double-pinyin and abbreviated pinyin, floating above the host window. The last piece of the Chinese-UI puzzle.

👉 **[Open the uIME repository](https://github.com/MikeWuPing/uIME)**

<a id="gufile-en"></a>

#### gufile

**Graphic UEFI File Manager** ｜ ★2 ｜ Category: Tool ｜ Language: 二进制发布（无源码） ｜ License: —

<img src="assets/gufile.png" width="640" alt="gufile">

A GUI file manager for the UEFI Shell with an Explorer-style layout — directory tree, copy & paste, new folder, and the rest.

👉 **[Open the gufile repository](https://github.com/MikeWuPing/gufile)**

<a id="rustpaint-en"></a>

#### rustpaint

**A UEFI Paint App in Rust** ｜ ★1 ｜ Category: Tool ｜ Language: Rust ｜ License: MIT

<img src="assets/rustpaint.png" width="640" alt="rustpaint">

A small UEFI paint application written in Rust with LVGL doing the rendering — Rust logic, EDK2 linking, LVGL drawing, complete with a toolbar, palette and status bar.

👉 **[Open the rustpaint repository](https://github.com/MikeWuPing/rustpaint)**


### 🧠 Skills

<a id="emulator-uefi-shell-app-en"></a>

#### emulator-uefi-shell-app

**UEFI Shell App Development Skill** ｜ ★70 ｜ Category: Skill ｜ Language: PowerShell ｜ License: —

<img src="assets/emulator-uefi-shell-app.png" width="640" alt="emulator-uefi-shell-app">

A complete knowledge base for Claude Code on UEFI Shell application development — the full path from environment setup to debug and deployment, with reusable build and QEMU test script templates.

👉 **[Open the emulator-uefi-shell-app repository](https://github.com/MikeWuPing/emulator-uefi-shell-app)**

<a id="pdf2md-en"></a>

#### pdf2md

**PDF to Markdown** ｜ ★65 ｜ Category: Skill ｜ Language: Python ｜ License: —

<img src="assets/pdf2md.png" width="640" alt="pdf2md">

Batch-converts PDF technical documents (datasheets, reference manuals, specs) into clean Markdown — table structures preserved, embedded images extracted, watermarks removed automatically.

👉 **[Open the pdf2md repository](https://github.com/MikeWuPing/pdf2md)**

<a id="pdf-watermark-removal-en"></a>

#### pdf-watermark-removal

**PDF Watermark Removal Skill** ｜ ★31 ｜ Category: Skill ｜ Language: Markdown Skill ｜ License: —

<img src="assets/pdf-watermark-removal.png" width="640" alt="pdf-watermark-removal">

A skill for Claude Code and OpenClaw: identifies and removes watermarks by analyzing the internal structure of a PDF, while keeping the legitimate content intact.

👉 **[Open the pdf-watermark-removal repository](https://github.com/MikeWuPing/pdf-watermark-removal)**

<a id="bios-security-analysis-en"></a>

#### bios-security-analysis

**BIOS Firmware Security Analysis Skill** ｜ ★17 ｜ Category: Skill ｜ Language: Python ｜ License: MIT

<img src="assets/bios-security-analysis.png" width="640" alt="bios-security-analysis">

A UEFI / BIOS firmware vulnerability analysis skill for Claude Code: firmware image parsing, deep decompression, microcode extraction, certificate auditing — all the way through to the final report.

👉 **[Open the bios-security-analysis repository](https://github.com/MikeWuPing/bios-security-analysis)**

<a id="nes-reverse-engineering-en"></a>

#### nes-reverse-engineering

**NES ROM Reverse Engineering & Faithful Recreation Skill** ｜ ★5 ｜ Category: Skill ｜ Language: Python ｜ License: MIT

<img src="assets/nes-reverse-engineering.png" width="640" alt="nes-reverse-engineering">

A platform-agnostic methodology for reverse-engineering NES / Famicom ROMs into faithful recreations, with deep-dive references and a zero-dependency extraction template. Several UEFI games in this collection were built exactly this way.

👉 **[Open the nes-reverse-engineering repository](https://github.com/MikeWuPing/nes-reverse-engineering)**

<a id="tech-figures-en"></a>

#### tech-figures

**Technical Article Figure Skill** ｜ ★4 ｜ Category: Skill ｜ Language: Python ｜ License: MIT

<img src="assets/tech-figures.png" width="640" alt="tech-figures">

A skill for producing figures for technical articles: turns content into consistent diagrams, flowcharts and structural charts.

👉 **[Open the tech-figures repository](https://github.com/MikeWuPing/tech-figures)**

<a id="rust-in-edk2-uefi-app-en"></a>

#### rust-in-edk2-uefi-app

**Rust-in-EDK2 UEFI App Skill** ｜ ★2 ｜ Category: Skill ｜ Language: Python ｜ License: MIT

<img src="assets/rust-in-edk2-uefi-app.png" width="640" alt="rust-in-edk2-uefi-app">

A skill for building UEFI applications whose logic is Rust (cargo staticlib) while EDK2 links and LVGL renders — including the traps that fail silently.

👉 **[Open the rust-in-edk2-uefi-app repository](https://github.com/MikeWuPing/rust-in-edk2-uefi-app)**


### 🎮 Games

<a id="uefi-supermario-en"></a>

#### UEFI_SuperMario

**Super Mario Bros (UEFI Port)** ｜ ★36 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-supermario.png" width="640" alt="UEFI_SuperMario">

The NES classic ported to the UEFI Shell: GOP graphics, pure software rendering, no audio dependency. Runs under QEMU + OVMF or on real UEFI Shell hardware.

👉 **[Open the UEFI_SuperMario repository](https://github.com/MikeWuPing/UEFI_SuperMario)**

<a id="uefi-contra-en"></a>

#### UEFI_Contra

**Contra (UEFI Port)** ｜ ★27 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-contra.png" width="640" alt="UEFI_Contra">

A technical experiment porting the NES classic Contra to the UEFI Shell: runs as a UEFI application (.efi), draws through GOP, needs no operating system and only depends on UEFI firmware.

👉 **[Open the UEFI_Contra repository](https://github.com/MikeWuPing/UEFI_Contra)**

<a id="uefi-jackal-en"></a>

#### UEFI_Jackal

**Jackal (UEFI Recreation)** ｜ ★16 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-jackal.png" width="640" alt="UEFI_Jackal">

Rather than emulating NES hardware, it translates the original 6502 disassembly line by line into a platform-independent C core, then draws through UEFI GOP and takes input and timing from UEFI services — running natively under QEMU or on real UEFI hardware.

👉 **[Open the UEFI_Jackal repository](https://github.com/MikeWuPing/UEFI_Jackal)**

<a id="uefi-tank-en"></a>

#### UEFI_tank

**Battle City (1990 Classic)** ｜ ★13 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-tank.png" width="640" alt="UEFI_tank">

A top-down, fixed-map tank shooter running in the UEFI Shell, recreating the core gameplay of the 1990 NES classic Battle City.

👉 **[Open the UEFI_tank repository](https://github.com/MikeWuPing/UEFI_tank)**

<a id="uefi-battlecity-en"></a>

#### UEFI_battlecity

**Battle City (UEFI Port)** ｜ ★7 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-battlecity.png" width="640" alt="UEFI_battlecity">

The classic FC Battle City ported to the UEFI Shell: executed directly in the shell after firmware boot, rendered through GOP, driven by the Simple Text Input Protocol, with no operating system required.

👉 **[Open the UEFI_battlecity repository](https://github.com/MikeWuPing/UEFI_battlecity)**

<a id="uefi-goonies-en"></a>

#### UEFI_Goonies

**The Goonies (UEFI Recreation)** ｜ ★6 ｜ Category: Game ｜ Language: C ｜ License: NOASSERTION

<img src="assets/uefi-goonies.png" width="640" alt="UEFI_Goonies">

A recreation of Konami's 1986 The Goonies inside the UEFI Shell, following the same route as Jackal: a 6502 disassembly translated into a C core, drawn through GOP.

👉 **[Open the UEFI_Goonies repository](https://github.com/MikeWuPing/UEFI_Goonies)**

<a id="uefi-nesemu-en"></a>

#### UEFI_NesEmu

**NES Emulator (UEFI Port)** ｜ ★6 ｜ Category: Tool, Game ｜ Language: C ｜ License: —

<img src="assets/uefi-nesemu.png" width="640" alt="UEFI_NesEmu">

A pure-C NES emulator originally built on SDL3, ported to the UEFI Shell environment. It is both a tool and a game — the cartridge now runs inside the firmware. Listed under tools and under games.

👉 **[Open the UEFI_NesEmu repository](https://github.com/MikeWuPing/UEFI_NesEmu)**

<a id="uefi-salamander-en"></a>

#### UEFI_Salamander

**Salamander (UEFI Recreation)** ｜ ★6 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-salamander.png" width="640" alt="UEFI_Salamander">

A UEFI Shell recreation of Konami's 1986 Salamander / Life Force: the 6502 disassembly translated into a platform-independent C core, GOP graphics, verified on QEMU / OVMF.

👉 **[Open the UEFI_Salamander repository](https://github.com/MikeWuPing/UEFI_Salamander)**

<a id="uefi-snake-en"></a>

#### UEFI_Snake

**Snake** ｜ ★6 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-snake.png" width="640" alt="UEFI_Snake">

A Snake game running in the UEFI Shell. EDK2 platform, UEFI 2.7+, x64.

👉 **[Open the UEFI_Snake repository](https://github.com/MikeWuPing/UEFI_Snake)**

<a id="uefi-supermario-mver-en"></a>

#### UEFI_SuperMario_MVer

**Super Mario Bros (Modified UEFI Port)** ｜ ★5 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-supermario-mver.png" width="640" alt="UEFI_SuperMario_MVer">

A modified port of the NES Super Mario Bros: implemented in pure C on top of static 6502 decompilation, drawing through the GOP protocol, with no operating system required — it boots straight in QEMU or on real hardware.

👉 **[Open the UEFI_SuperMario_MVer repository](https://github.com/MikeWuPing/UEFI_SuperMario_MVer)**

<a id="uefi-sf3-en"></a>

#### UEFI_SF3

**Street Fighter III (NES, UEFI Recreation)** ｜ ★4 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-sf3.png" width="640" alt="UEFI_SF3">

The 6502 assembly of Street Fighter III (9 Fighter) as it ran on the NES, faithfully translated into C and reimplemented as a UEFI Shell application.

👉 **[Open the UEFI_SF3 repository](https://github.com/MikeWuPing/UEFI_SF3)**

<a id="uefi-shmup-en"></a>

#### UEFI_Shmup

**Space Fighter (Vertical Shoot-em-up)** ｜ ★3 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-shmup.png" width="640" alt="UEFI_Shmup">

A classic vertical scrolling shoot-em-up running entirely inside the UEFI Shell.

👉 **[Open the UEFI_Shmup repository](https://github.com/MikeWuPing/UEFI_Shmup)**

<a id="uefi-bomberman-en"></a>

#### UEFI_bomberman

**Bomberman** ｜ ★2 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-bomberman.png" width="640" alt="UEFI_bomberman">

The classic Bomberman running under the UEFI Shell.

👉 **[Open the UEFI_bomberman repository](https://github.com/MikeWuPing/UEFI_bomberman)**

<a id="uefi-breakout-en"></a>

#### UEFI_Breakout

**Breakout** ｜ ★1 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-breakout.png" width="640" alt="UEFI_Breakout">

A Breakout game running in the UEFI Shell.

👉 **[Open the UEFI_Breakout repository](https://github.com/MikeWuPing/UEFI_Breakout)**

<a id="uefi-pacman-en"></a>

#### UEFI_Pacman

**Pacman** ｜ ★1 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-pacman.png" width="640" alt="UEFI_Pacman">

A Pacman game running in the UEFI Shell.

👉 **[Open the UEFI_Pacman repository](https://github.com/MikeWuPing/UEFI_Pacman)**

<a id="uefi-tetris-en"></a>

#### UEFI_Tetris

**Tetris** ｜ ★1 ｜ Category: Game ｜ Language: C ｜ License: —

<img src="assets/uefi-tetris.png" width="640" alt="UEFI_Tetris">

A Tetris game running in the UEFI Shell.

👉 **[Open the UEFI_Tetris repository](https://github.com/MikeWuPing/UEFI_Tetris)**


### 📦 Others

<a id="disasm-goonies-en"></a>

#### disasm_Goonies

**The Goonies (RC809) Full ROM Disassembly** ｜ ★1 ｜ Category: Other ｜ Language: Assembly ｜ License: —

<img src="assets/disasm-goonies.png" width="640" alt="disasm_Goonies">

A complete disassembly project for the NES ROM of The Goonies (Konami, 1986, Japanese release RC809) — the groundwork the UEFI recreation was built on.

👉 **[Open the disasm_Goonies repository](https://github.com/MikeWuPing/disasm_Goonies)**


---

## License

Each project is governed by its own license, documented in its own repository. The tools inside the `UEFI_Test_Suite` suite are **free for personal use; commercial use requires written authorization from the author** (mikewuping@163.com).

## Contact

Mike Wu — [@MikeWuPing](https://github.com/MikeWuPing) · mikewuping@163.com
