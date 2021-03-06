﻿# [GD32V103](https://github.com/SoCXin/GD32V103)

[![sites](http://182.61.61.133/link/resources/SoC.png)](http://www.SoC.Xin)

#### [Vendor](https://github.com/SoCXin/Vendor) ：[GigaDevice](https://github.com/SoCXin/GigaDevice)
#### [Core](https://github.com/SoCXin/RISC-V)：[Nuclei Bumblebee](https://github.com/SoCXin/RISC-V)
#### [Level](https://github.com/SoCXin/Level)：108MHz

### [GD32V103描述](https://github.com/SoCXin/GD32V103/wiki)

[GD32V103](https://github.com/SoCXin/GD32V103) 基于RISC-V的Bumblebee内核，支持RV32IMAC指令子集的组合，处理器频率108MHz，16-128KB的片上闪存和6-32KB的SRAM。在最高主频下的工作性能可达153 DMIPS，CoreMark®测试也取得了360分的优异表现，相比GD32 Cortex®-M3内核产品性能提升15%的同时，动态功耗降低了50%，待机功耗更降低了25%。

支持32位宽的标准AHB-Lite系统总线接口，主流支持标准JTAG接口和RISC-V调试标准。

芯来科技(Nuclei System Technology)的 Bumblebee内核支持定制化指令，优化了中断处理机制，配备了64位宽的实时计时器、可以产生RISC-V标准定义的计时器中断，还支持数十个外部中断源，具有16个中断级别和优先级，并支持中断嵌套和快速向量中断处理机制。低功耗管理可以支持两级休眠模式。支持标准JTAG接口及RISC-V调试标准， 适用于硬件断点和交互式调试。Bumblebee内核也支持RISC-V标准的编译工具链，以及Linux/Windows图形化集成开发环境。

Bumblebee内核能够以二级流水线的代价，达到传统架构三级流水线的性能和频率，使得GD32VF103系列MCU在最高主频下的工作性能可达153 DMIPS，CoreMark®测试也取得了360分，相比GD32 Cortex®-M3内核产品性能提升15%，动态功耗降低了50%，待机功耗更降低了25%。

### 关键参数

* 12bit高精度ADC + DAC，ADC采样率高达2.6M SPS，多达16个可复用通道，支持16-bit硬件过采样滤波功能和分辨率可配置功能。
* USBFS/CAN/I2S/I2C/SPI，2.6V-3.6V供电，I/O口可承受5V电平

### [资源收录](https://github.com/SoCXin/GD32V103)

* [文档](docs/)
* [资源](src/)
* [工程](project/)

### [选型建议](https://github.com/SoCXin/GD32V)

[GD32V103](https://github.com/SoCXin/GD32V103) 系列对标的是[STM32F103](https://github.com/SoCXin/STM32F103),在成本和外设相似的情况下具有更高的性能。

###  [SoC芯平台](http://www.SoC.Xin)
