<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:E6D6F5,100:9F7AEA&height=180&section=header&text=Tishya%20Yadlapalli&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Embedded%20%E2%80%A2%20Firmware%20%E2%80%A2%20ML&descAlignY=58&descSize=16" />

<table border="0">
<tr>
<td width="65%" valign="middle">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=9F7AEA&vCenter=true&width=440&lines=Hi%2C+I'm+Tishya;Embedded+systems+and+firmware;Real-time+systems+and+peripherals;ML+on+constrained+hardware" alt="Hi, I'm Tishya. Embedded systems and firmware." />

B.Tech ECE student at IIIT Sri City (2024–2028), focused on embedded systems and firmware.

- Wrote the firmware for [Walkman](https://github.com/guthib-iiits/walkman-imagined), an STM32H743 audio player: CS43131 DAC over SAI DMA, MP3/WAV streaming, UC8151D e-paper UI, FatFs on SD and eMMC, USB mass storage (compiles; bring-up on the board is next)
- Built [DermEdge](https://github.com/Lilac-dot/DermEdge): on-device eczema screening with CLIP in the browser (ONNX Runtime Web) and an ESP32 wristband, tested as a breadboard prototype, that detects scratching from an ADXL345. [Live demo](https://derm-edge.vercel.app)
- Built an [ESP32 graphics engine](https://github.com/Lilac-dot/ESP32-DMA-Snake-Game) in ESP-IDF with DMA-driven SPI rendering and a custom framebuffer
- [Edge ML research](https://github.com/Lilac-dot/eczema-detection): INT8 quantization and pruning of 9 CNNs; found a PyTorch qnnpack quantization bug and a workaround

<a href="https://www.linkedin.com/in/tishya-yadlapalli-813591318"><img src="https://img.shields.io/badge/LinkedIn-9F7AEA?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<img src="https://img.shields.io/badge/B.Tech%20ECE-IIIT%20Sri%20City-C4A7E7?style=for-the-badge" />

</td>
<td width="35%" align="center" valign="middle">

<img src="./assets/pixel-cat.svg" width="184" alt="pixel cat sitting on a microcontroller" />

</td>
</tr>
</table>

---

### Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,py,arduino,matlab,pytorch,git,latex,linux,vscode&theme=light&perline=10" />

<br/><br/>

<img src="https://img.shields.io/badge/ESP--IDF-E6D6F5?style=flat-square&logo=espressif&logoColor=9F7AEA" />
<img src="https://img.shields.io/badge/FreeRTOS-E6D6F5?style=flat-square" />
<img src="https://img.shields.io/badge/STM32-E6D6F5?style=flat-square&logo=stmicroelectronics&logoColor=9F7AEA" />
<img src="https://img.shields.io/badge/STM32CubeMX-E6D6F5?style=flat-square&logo=stmicroelectronics&logoColor=9F7AEA" />
<img src="https://img.shields.io/badge/STM32CubeIDE-E6D6F5?style=flat-square&logo=stmicroelectronics&logoColor=9F7AEA" />
<img src="https://img.shields.io/badge/8051%20%2F%208086-E6D6F5?style=flat-square" />
<img src="https://img.shields.io/badge/LTspice-E6D6F5?style=flat-square" />
<img src="https://img.shields.io/badge/QCADesigner-E6D6F5?style=flat-square" />

</div>

---

### Currently working on

- **[GroundWatch](https://github.com/Lilac-dot/GroundWatch)**: seismic intrusion detection and localization on an 8052 (AT89S52). Three buried piezos plus PIR, magnetometer and microphone, a 1 ms ISR for feature extraction and a task scheduler. Firmware done, wiring up the hardware now. Team project
- **[DermEdge band](https://github.com/Lilac-dot/DermEdge/tree/main/firmware_dermedge/band)**: taking the ESP32 wristband from breadboard to a wearable prototype, and moving scratch detection to faster ADXL345 sampling
- **[QCA time-to-digital converter](https://github.com/Lilac-dot/Time-to-Digital-Converter-QCA)**: replicating an IEEE Access 2025 design in QCADesigner. The conventional TDC reproduces; the paper's proposed design doesn't yet, traced to a clock-zone conflict. Team project

---

### Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lilac-dot/Lilac-dot/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Lilac-dot/Lilac-dot/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Lilac-dot/Lilac-dot/output/github-snake.svg" />
</picture>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:9F7AEA,100:E6D6F5&height=100&section=footer" />

<sub>Snake by <a href="https://github.com/Platane/snk">Platane/snk</a> (MIT).</sub>
