# Vivado_benchmark 

## Quick Navigation
- [English](#vivado_benchmark-project)
- [中文](#vivado_benchmark-项目)

---

## Vivado_benchmark Project

This project benchmarks the synthesis of Vivado's TMR Microblaze Example on the KCU105 target board.

### Benchmark Configuration
During the creation of the block design, the Synthesis Options were set to Global.

### Benchmark Results

Excited to see your test results!

| Number | CPU          | Memory                               | OS            | Version | Number of jobs | Synthesis | Implementation | Remarks                                                                 |
|--------|--------------|--------------------------------------|---------------|---------|----------------|-----------|----------------|--------------------------------------------------------------------------|
| 1      | Ryzen 9 7945HX | 96GB DDR5 Dual-Channel 5000MHz | Windows 11 23H2 | 2022.2  | 8              | 00:15:35  | 00:28:43       | Threads are bounded to the SMT-0 cores of CCD1                          |
| 2      | Core i7 14650HX | 32GB DDR5 Dual-Channel 5600MHz | Windows 11 23H2 | 2022.2  | 8              | 00:10:29  | 00:23:50       |                         |
| 3      | Core i5 12490F  | 32GB DDR5 Dual-Channel 5600MHz | Windows 10 21H2 | 2022.2  | 8              | 00:12:14  | 00:27:31       |                         |

---

## Vivado_benchmark 项目

本项目对 Vivado 中的 TMR Microblaze 示例进行综合性能基准测试，目标平台为 KCU105。

### 配置说明
在create block design时，将综合选项设置为 Global。

### 基准测试结果

欢迎提供测试结果！

| 编号 | CPU          | 内存                                  | 操作系统        | 版本   | 工作数          | 综合时间  | 实施时间       | 备注                                                                       |
|------|--------------|--------------------------------------|---------------|--------|-----------------|-----------|----------------|----------------------------------------------------------------------------|
| 1    | Ryzen 9 7945HX | 96GB DDR5 双通道 5000MHz | Windows 11 23H2 | 2022.2 | 8               | 00:15:35  | 00:28:43       | 线程绑定至 CCD1 的 SMT-0 核心                                             |
| 2    | Core i7 14650HX | 32GB DDR5 双通道 5600MHz | Windows 11 23H2 | 2022.2  | 8              | 00:10:29  | 00:23:50       |                         |
| 3    | Core i5 12490F  | 32GB DDR5 双通道 5600MHz | Windows 10 21H2 | 2022.2  | 8              | 00:12:14  | 00:27:31       |                         |

---
