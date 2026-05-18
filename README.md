# 2.13 寸 410×502 AMOLED MIPI 模组（ST7801）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 2.13 英寸 **AMOLED**，分辨率 **410×502** |
| 接口 | **MIPI** |
| 驱动芯片 | **ST7801** |
| 规格标识 | 产品资料中常用 **`2.13-amoled-410x502-mipi-st7801`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、接口与初始化相关文档 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF代码**（esp-lvgl-port + LVGL9） |
| `with-te/` | **屏幕防撕裂代码** |
| `eaf/` | **EAF动画代码** |
| `display-touch-test/` | **显示和触摸单独测试程序** |

### 示例工程路径

#### 基础（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_ST7801-MIPI_ESP-LVGL-PORT_V9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| LVGL 通用演示 | `examples/with-te/p4-idf_st7801-mipi_lvgl_common_demo/` |

#### EAF动画代码（`eaf/`）

| 说明 | 路径 |
|:--|:--|
| esp-lv-eaf-player | `examples/eaf/p4-idf_st7801-mipi_esp-lv-eaf-player/` |

#### 显示和触摸单独测试程序（`display-touch-test/`）

| 说明 | 路径 |
|:--|:--|
| ST7801 MIPI 显示测试 | `examples/display-touch-test/st7801_mipi_dsi/` |
| CST820 触摸 I2C 测试 | `examples/display-touch-test/P4-IDF_CST820-I2C/` |
