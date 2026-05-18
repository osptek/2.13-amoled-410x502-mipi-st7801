# 2.13" 410×502 AMOLED MIPI module (ST7801) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 2.13-inch **AMOLED** panel, **410×502** resolution |
| Interface | **MIPI** |
| Driver IC | **ST7801** |
| Spec ID | **`2.13-amoled-410x502-mipi-st7801`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, interface and initialization documentation |
| `examples/` | **Sample projects** grouped by feature |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (esp-lvgl-port + LVGL9) |
| `with-te/` | Tear-related samples (**屏幕防撕裂代码**) |
| `eaf/` | EAF animation (**EAF动画代码**) |
| `display-touch-test/` | Display and touch tests (**显示和触摸单独测试程序**) |

### Sample project paths

#### Baseline (`examples/` root)

| Description | Path |
|:--|:--|
| esp-lvgl-port + LVGL9 | `examples/P4-IDF_ST7801-MIPI_ESP-LVGL-PORT_V9/` |

#### Tear-related (`with-te/`)

| Description | Path |
|:--|:--|
| LVGL common demo | `examples/with-te/p4-idf_st7801-mipi_lvgl_common_demo/` |

#### EAF (`eaf/`)

| Description | Path |
|:--|:--|
| esp-lv-eaf-player | `examples/eaf/p4-idf_st7801-mipi_esp-lv-eaf-player/` |

#### Display and touch tests (`display-touch-test/`)

| Description | Path |
|:--|:--|
| ST7801 MIPI display test | `examples/display-touch-test/st7801_mipi_dsi/` |
| CST820 touch I2C test | `examples/display-touch-test/P4-IDF_CST820-I2C/` |
