# Hi, I'm Rosalie 👋

**开源硬件 / 嵌入式 · Open-source hardware & embedded systems**

![Focus](https://img.shields.io/badge/focus-power%20electronics%20%7C%20embedded-1E90FF)
![Tools](https://img.shields.io/badge/toolchain-EasyEDA%20Pro%20%7C%20C%20%7C%20APM32-00599C)
![License](https://img.shields.io/badge/prefers-GPL--3.0-blue)

我在做模块化电源与电源监测类的开源硬件，喜欢把设计文件、BOM、固件和踩坑记录一起开放出来。

*I build open-source power electronics — schematics, BOM, firmware and field notes all published.*

---

## 🔧 当前项目 · Featured Project

### [OpenPowerLab](https://github.com/rosaliehhh666-del/OpenPowerLab)

开源模块化直流稳压电源与电源拓展板。可调电源板已完成焊接验证；电源拓展板基于 APM32F030C8T6 + INA4181，实现 4 路电压电流实时监测。

| 模块 | 说明 |
| --- | --- |
| **可调电源板** | 3 路可选输入（DC / USB-C PD / 接线端子），9–20 V；+3.3 V / +5 V / −5 V 固定输出 + 2 路可调输出；XL4015 + XL6019 方案 |
| **电源拓展板** | 将上述各路电源扩展为多路 XH2.54 接口，并用 INA4181 四通道电流检测实现电压/电流/功率实时采集与 OLED 显示 |

[![Repo](https://img.shields.io/badge/repo-OpenPowerLab-181717?logo=github)](https://github.com/rosaliehhh666-del/OpenPowerLab)
![License: GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue)

---

## 🛠 技术栈 · Toolbox

| 领域 | 使用 |
| --- | --- |
| **原理图 / PCB** | 立创 EDA 专业版 (EasyEDA Pro)、LCSC 元器件库 |
| **电源拓扑** | Buck (XL4015)、反激/升压负压 (XL6019)、LDO、USB-C PD 诱骗 (CH224K) |
| **MCU / 固件** | APM32F030 (Cortex-M0)、C99、标准外设库、SPI / I2C / ADC / UART |
| **调试** | SWD (J-Link / DAP-Link / ST-Link)、示波器、电子负载、限流电源 |

---

## 📌 一些原则 · How I work

- **能复刻才算开源**：设计源文件、Gerber、BOM、固件缺一不可
- **标称 ≠ 实测**：没测过的参数一律标注「标称 / 未验证」
- **先学会再发布**：第一次画电源板，欢迎指正 —— issue 和 PR 都很有价值

---

## 📫 联系 · Contact

- 有问题请优先在对应仓库开 [Issue](https://github.com/rosaliehhh666-del/OpenPowerLab/issues)
- 邮件：3465531473@qq.com

<sub>Everything I publish is under GPL-3.0 unless stated otherwise. 电源有风险，上电请限流。</sub>
