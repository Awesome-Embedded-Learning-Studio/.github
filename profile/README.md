<div align="center">
  <img src="AELS-Header-Logo-Light.png#gh-light-mode-only" alt="Awesome Embedded Learning Studio" width="760" />
  <br />
  <img width="64" src="Awesome-Embedded.png" alt="Awesome-Embedded logo" /> 

  <p><strong>一个持续尝试现代 C++、横跨 MCU 与嵌入式 Linux 的嵌入式开源学习工作室</strong></p>
  <p><em>Keep it small, make it fun ✨</em></p>

  <p>
    <a href="https://awesome-embedded-learning-studio.github.io/Awesome-Embedded/">
      <img src="https://img.shields.io/badge/📖_文档站-点击我进入在线阅读-6366f1?style=for-the-badge" alt="文档站" />
    </a>
    &nbsp;
    <a href="https://github.com/orgs/Awesome-Embedded-Learning-Studio/discussions">
      <img src="https://img.shields.io/badge/💬_讨论区-点击我加入交流-22c55e?style=for-the-badge" alt="讨论区" />
    </a>
    &nbsp;
    <a href="https://awesome-embedded-learning-studio.github.io/Awesome-Embedded/roadmap/">
      <img src="https://img.shields.io/badge/🧭_学习地图-选择一条路线-f59e0b?style=for-the-badge" alt="学习地图" />
    </a>
  </p>
</div>

---

我们把嵌入式学习拆成一组可以真正动手的项目：从工具与 C/C++ 基础出发，进入 STM32F1、ESP32-S3、嵌入式 Linux、Qt 与系统软件实验。这里的仓库不是单纯资料索引，而是围绕教程、源码、工具链、模拟环境和真实硬件验证逐步搭起来的学习工作台。

## 🚀 从这里开始

| 目标 | 推荐入口 |
| --- | --- |
| 💻 系统学习现代 C++ | [Tutorial_AwesomeModernCPP](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_AwesomeModernCPP)<br /><sub>从 C++11 到 C++23，并把工程方法带进 MCU、Linux 与系统软件</sub> |
| 🎨 学 Qt / 嵌入式 GUI | [Tutorial_AwesomeQt](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_AwesomeQt) · [CFDesktop](https://github.com/Awesome-Embedded-Learning-Studio/CFDesktop)<br /><sub>教程、桌面框架与产品化实验</sub> |
| 🐧 上手 Embedded Linux | [imx-forge](https://github.com/Awesome-Embedded-Learning-Studio/imx-forge) · [rk-forge](https://github.com/Awesome-Embedded-Learning-Studio/rk-forge) · [PenguinLab](https://github.com/Awesome-Embedded-Learning-Studio/PenguinLab)<br /><sub>i.MX6ULL 入门，Rockchip 横跨 32/64 位，H618 提供主线化横向参考</sub> |
| 🔩 做 MCU 裸机项目 | [ST-Forge](https://github.com/Awesome-Embedded-Learning-Studio/ST-Forge) · [BareMetal-Drivers](https://github.com/Awesome-Embedded-Learning-Studio/BareMetal-Drivers) · [micro-forge](https://github.com/Awesome-Embedded-Learning-Studio/micro-forge)<br /><sub>STM32F1 公开主线；ESP32-S3 路线仍在私有仓规划</sub> |
| 🧠 研究系统软件 | [CFBox](https://github.com/Awesome-Embedded-Learning-Studio/CFBox) · [Cinux](https://github.com/Awesome-Embedded-Learning-Studio/Cinux) · [Cinux-Book](https://github.com/Awesome-Embedded-Learning-Studio/Cinux-Book)<br /><sub>Unix 工具集、x86_64 OS 实验与配套教程</sub> |

## 🧭 项目主线

| 主线 | 做什么 | 代表仓库 |
| --- | --- | --- |
| 💻 **Modern C++** | 贯穿 MCU、Linux、系统软件与产品项目的工程方法 | [Tutorial_AwesomeModernCPP](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_AwesomeModernCPP) · [aex](https://github.com/Awesome-Embedded-Learning-Studio/aex)<br />[CFBox](https://github.com/Awesome-Embedded-Learning-Studio/CFBox) · [edgecv](https://github.com/Awesome-Embedded-Learning-Studio/edgecv) |
| 🐧 **Embedded Linux** | BSP、启动链、交叉编译、内核调试与 rootfs | [imx-forge](https://github.com/Awesome-Embedded-Learning-Studio/imx-forge) · [rk-forge](https://github.com/Awesome-Embedded-Learning-Studio/rk-forge) · [h618_forge](https://github.com/Awesome-Embedded-Learning-Studio/h618_forge)<br />[PenguinLab](https://github.com/Awesome-Embedded-Learning-Studio/PenguinLab) |
| 🧠 **Linux / System Programming** | 从 userspace 工具到 x86_64 OS 实验 | [Cinux](https://github.com/Awesome-Embedded-Learning-Studio/Cinux) · [Cinux-Book](https://github.com/Awesome-Embedded-Learning-Studio/Cinux-Book)<br />[CFBox](https://github.com/Awesome-Embedded-Learning-Studio/CFBox) |
| 🔩 **MCU / RTOS** | STM32F1、ESP32-S3、裸机驱动、RTOS 与 Cortex-M 模拟实验 | [ST-Forge](https://github.com/Awesome-Embedded-Learning-Studio/ST-Forge) · [BareMetal-Drivers](https://github.com/Awesome-Embedded-Learning-Studio/BareMetal-Drivers)<br />[micro-forge](https://github.com/Awesome-Embedded-Learning-Studio/micro-forge) |
| 🎨 **Qt / GUI** | Qt 6 教程、桌面框架与 ARM 交叉编译流水线 | [Tutorial_AwesomeQt](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_AwesomeQt)<br />[CFDesktop](https://github.com/Awesome-Embedded-Learning-Studio/CFDesktop) · [qt-compile-pipeline](https://github.com/Awesome-Embedded-Learning-Studio/qt-compile-pipeline) |

完整项目矩阵、状态和学习路径请看：[文档站 · 项目一览](https://awesome-embedded-learning-studio.github.io/Awesome-Embedded/projects/)。

## 🤝 协作方式

- 有问题、想法或路线建议：到 [Discussions](https://github.com/orgs/Awesome-Embedded-Learning-Studio/discussions) 发帖。
- 想参与仓库建设：先看 [贡献指南](https://awesome-embedded-learning-studio.github.io/Awesome-Embedded/contributing/)。
- 想了解接下来会做什么：查看 [Roadmap](https://awesome-embedded-learning-studio.github.io/Awesome-Embedded/roadmap/)。

## 🛠️ 维护者

<table align="center">
  <tr>
    <td align="center">
      <a href="https://github.com/HNHKHNH">
        <img width="72" src="https://github.com/HNHKHNH.png?size=144" alt="HNHKHNH" /><br />
        <strong>HNHKHNH</strong>
      </a>
      <br />
      <sub>硬件 / PCB</sub>
    </td>
    <td align="center">
      <a href="https://github.com/Charliechen114514">
        <img width="72" src="https://github.com/Charliechen114514.png?size=144" alt="Charliechen114514" /><br />
        <strong>Charliechen114514</strong>
      </a>
      <br />
      <sub>C / C++ / 系统软件</sub>
    </td>
    <td align="center">
      <a href="https://github.com/Leon19960120">
        <img width="72" src="https://github.com/Leon19960120.png?size=144" alt="Leon19960120" /><br />
        <strong>Leon19960120</strong>
      </a>
      <br />
      <sub>文档审校 / 工程勘误</sub>
    </td>
  </tr>
</table>

---

<div align="center">
  <sub>Released under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</sub>
  <br />
  <br />
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Awesome-Embedded-Learning-Studio.Awesome-Embedded-Learning-Studio" alt="visitor badge" />
</div>
