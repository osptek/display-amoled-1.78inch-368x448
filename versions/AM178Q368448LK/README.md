<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.78″ AMOLED 显示屏 368×448（AM178Q368448LK）</h1>

<p align="center"><b>AMOLED 模组 · QSPI · CO5300</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: CO5300" src="https://img.shields.io/badge/Driver-CO5300-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.78 寸 368×448 AMOLED 模组宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.78 英寸 |
| 类型 | AMOLED |
| 分辨率 | 368×448 |
| 外形尺寸 | 34.14 x 42.74 mm |
| 有效显示区域 | 28.70 x 34.94 mm |
| 接口 | QSPI |
| 驱动 IC | CO5300 |
| 触摸驱动 | — |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf`](./datasheets/CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf) |
| 规格文档 | [`DS_CHSC_6417_EU_24_v1_3_1_f66256c159.pdf`](./datasheets/DS_CHSC_6417_EU_24_v1_3_1_f66256c159.pdf) |
| 规格文档 | [`AM178Q368448LK.pdf`](./datasheets/AM178Q368448LK.pdf) |
| CAD 图纸 | [`AM178Q368448LK1.dwg`](./cad/AM178Q368448LK1.dwg) |
| CAD 图纸 | [`OK-14F024-04.pdf`](./cad/OK-14F024-04.pdf) |
| 转接板资料 | [`转接板1 原理图1.96_1.78_AMOLED转接板V1.0.pdf`](./adapter/%E8%BD%AC%E6%8E%A5%E6%9D%BF1%20%E5%8E%9F%E7%90%86%E5%9B%BE1.96_1.78_AMOLED%E8%BD%AC%E6%8E%A5%E6%9D%BFV1.0.pdf) |
| 转接板资料 | [`转接板2 原理图-1.78demo转接板.pdf`](./adapter/%E8%BD%AC%E6%8E%A5%E6%9D%BF2%20%E5%8E%9F%E7%90%86%E5%9B%BE-1.78demo%E8%BD%AC%E6%8E%A5%E6%9D%BF.pdf) |

## 仓库结构

```text
display-amoled-1.78inch-368x448/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── AM178Q368448LK/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        └── adapter/          # 转接板资料 + 转接板图片
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
