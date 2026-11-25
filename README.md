# High-Voltage Sensing Circuit (STM32H503 & LoRa) | 高電圧センシング回路

[English](#english) | [日本語](#日本語)

---

## English

A hardware design for a **High-Voltage (up to 15,000V / 15kV) and Current Sensing board** featuring an **STM32H503** microcontroller and **LoRa wireless communication**, created in **Altium Designer**.

> **⚠️ EXTREME HIGH VOLTAGE WARNING (15kV):** This circuit handles up to **15,000V**. Do not build, test, or probe this hardware without proper high-voltage qualifications, certified isolation, and safety protocols.

### Key Features
* **Max Input Voltage:** 15,000V (15kV)
* **Sensing & Control:** High-voltage divider and current sensing (`Voltage_Sense.SchDoc`, `Current_Sense.SchDoc`), STM32H503 MCU (`MCU_Module.SchDoc`) with STDC14 debug interface, and 12-DIP LoRa module (`LoRaModule.SchDoc`).
* **Power & Status:** Dedicated power regulation (`Power_Module.SchDoc`) and status LEDs (`LED_blink.SchDoc`).

### Quick Start
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Open in Altium Designer:** Launch `2027_09_15_RVM_EF_ver0.4.PrjPcb` (custom libraries are included locally). Licensed under the **MIT License**.

---

## 日本語

オンボードの **STM32H503** マイコンと **LoRa無線通信** を搭載した、**最大15,000V（15kV）対応の高電圧・電流センシング基板**（Altium Designer設計データ）です。

> **⚠️ 超高電圧に関する警告（15kV）：** 本回路は最大 **15,000V** を扱います。高電圧に関する資格や適切な安全対策がない状態での製作・テスト・測定は行わないでください。

### 主な特徴
* **最大入力電圧:** 15,000V (15kV)
* **構成要素:** 高電圧・電流分圧回路 (`Voltage_Sense.SchDoc`, `Current_Sense.SchDoc`)、STM32H503マイコン (`MCU_Module.SchDoc` / STDC14インターフェース)、LoRa無線モジュール (`LoRaModule.SchDoc`)、および電源レギュレータ (`Power_Module.SchDoc`, `LED_blink.SchDoc`)。

### はじめに
1. **リポジトリのクローン：**
   ```bash
   git clone https://github.com
   ```
2. **Altium Designerで開く：** `2027_09_15_RVM_EF_ver0.4.PrjPcb` を開きます（ライブラリは同梱）。**MITライセンス**。
