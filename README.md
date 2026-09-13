# PCB CAD 风格 Stroke 字体

本仓库提供一组 TrueType 字体，用于模拟 Cadence Allegro 和 PADS 传统 stroke/vector 字体的视觉风格。它们主要用于 Altium Designer、KiCad、绘图工具、文档排版工具，以及其他支持系统字体的 PCB/EDA/CAD 场景。

## 字体家族

- `Allegro Style`
  - `Allegro Style Thin`
  - `Allegro Style Regular`
  - `Allegro Style Bold`
- `Pads Style`
  - `Pads Style Thin`
  - `Pads Style Regular`
  - `Pads Style Bold`

## 用途

许多 PCB 装配图、加工图、丝印说明和制造说明使用 Allegro 或 PADS 中的传统矢量/单线字体。若在 Altium Designer 或其他软件中复现这些图纸，默认系统字体往往与原图风格差异明显。

本项目的目标是让这些传统 PCB 字体风格可以在其他软件中更方便地复现。适用场景包括：

- 复刻旧版装配图中的 NOTES 字体风格；
- 在 Altium 中模拟 Allegro/PADS 的文字观感；
- 制作文档、PDF、截图时保持 PCB CAD 图纸风格；
- 在不同 PCB 工具之间保持注释文字风格一致。

## 来源说明

这些字形通过分析 Allegro/PADS 风格 stroke 字体的显示与导出效果，并将 stroke 字形转换为 TrueType 轮廓字体得到。它们是用于视觉匹配的兼容性字体，并不是 Cadence、Siemens、Mentor Graphics 或其他 EDA 厂商发布的官方字体。

生成的字体可视作风格兼容的近似版本，不声称与原厂字体完全一致，也不表示获得原软件厂商认可或授权。

## 使用方法

1. 安装 `.ttf` 字体文件。
2. 如果目标软件已经打开，重启该软件。
3. 在软件中选择对应字体，例如：
   - `Allegro Style Thin`
   - `Allegro Style Regular`
   - `Allegro Style Bold`
   - `Pads Style Thin`
   - `Pads Style Regular`
   - `Pads Style Bold`

在 Altium Designer 中，可以将这些字体作为普通 TrueType 字体用于 PCB 文字、制图说明或类似装配图注释的文本。

## 使用建议

- 如果字体没有立即出现，请重启 Altium Designer、Word 或对应软件。
- 在 Windows 上，安装新版前建议先卸载旧版同名字体，否则字体缓存可能仍调用旧版本。
- 不同软件的字体栅格化方式不同，因此在 Altium、Word、PDF 阅读器和浏览器中的线宽与字距可能略有差异。

## 免责声明

本项目是独立的兼容性/视觉匹配项目，与 Cadence Design Systems、Siemens EDA、Mentor Graphics、PADS、Altium 或相关公司无隶属、背书或赞助关系。

Cadence、Allegro、PADS、Siemens、Mentor Graphics、Altium 等名称是其各自所有者的商标或注册商标。本文中仅用于描述视觉兼容目标和使用场景。

在公开分发生成字体或相关源数据前，请自行确认原软件、原始字体数据、导出数据或逆向材料的许可条款。


---


# PCB CAD Stroke Style Fonts

This repository provides TrueType fonts that approximate the legacy stroke-text appearance used by Cadence Allegro and PADS. The fonts are intended for use in PCB design tools that support system fonts, such as Altium Designer, KiCad, drawing tools, documentation workflows, and other EDA/CAD-adjacent environments.

## Font Families

- `Allegro Style`
  - `Allegro Style Thin`
  - `Allegro Style Regular`
  - `Allegro Style Bold`
- `Pads Style`
  - `Pads Style Thin`
  - `Pads Style Regular`
  - `Pads Style Bold`

## Purpose

Many PCB assembly drawings, fabrication drawings, and silkscreen notes use legacy vector/stroke lettering from tools such as Cadence Allegro or PADS. When these drawings are reproduced in Altium Designer or other software, the default system fonts often look visibly different.

These TTF fonts were created to make that style easier to reproduce outside the original EDA tools. They are useful for:

- matching legacy assembly drawing notes;
- making Altium text resemble Allegro/PADS stroke text;
- preparing documentation, PDFs, or screenshots with a CAD-like PCB lettering style;
- keeping annotation style consistent across different PCB tools.

## Notes On Origin

The shapes were reconstructed by studying the behavior and exported appearance of Allegro/PADS-style stroke fonts, then converting the stroke-style glyphs into TrueType outline fonts. The result is a practical compatibility font for visual matching, not an official font package from Cadence, Siemens, Mentor Graphics, or any other EDA vendor.

The generated fonts are provided as style-compatible approximations. They are not claimed to be identical to, endorsed by, or distributed by the original software vendors.

## Usage

1. Install the `.ttf` files on your operating system.
2. Restart the target application if it was already open.
3. Select one of the installed families, for example:
   - `Allegro Style Thin`
   - `Allegro Style Regular`
   - `Allegro Style Bold`
   - `Pads Style Thin`
   - `Pads Style Regular`
   - `Pads Style Bold`

In Altium Designer, use these as standard TrueType fonts for PCB text, documentation text, or drafting-style notes.

## Practical Tips

- If the new font does not appear immediately, restart Altium Designer, Word, or the relevant application.
- On Windows, uninstall older versions of the same font before installing a new build, otherwise the font cache may continue using an old version.
- Different programs rasterize fonts differently, so stroke thickness and spacing may look slightly different between Altium, Word, PDF viewers, and browsers.

## Disclaimer

This project is an independent compatibility/visual-matching effort. It is not affiliated with, endorsed by, or sponsored by Cadence Design Systems, Siemens EDA, Mentor Graphics, PADS, Altium, or any related company.

Cadence, Allegro, PADS, Siemens, Mentor Graphics, and Altium are trademarks or registered trademarks of their respective owners. They are mentioned only to describe visual compatibility and intended use.

Before redistributing generated fonts or source data, check the license terms of any original software, font data, exported data, or reverse-engineered materials used in your workflow.
