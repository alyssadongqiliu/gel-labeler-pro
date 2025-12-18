# Gel Labeler Pro / 电泳胶孔标记工具专业版

## 简介 / Introduction
Gel Labeler Pro 是一款专为生物实验室设计的轻量级网页工具，用于快速、准确地标记电泳胶图片（Gel Electrophoresis Images）。无需安装任何软件，直接在浏览器中打开即可使用。支持批量标记、参考 Ladder 对比、以及多种导出格式。

Gel Labeler Pro is a lightweight web-based tool designed for biology labs to quickly and accurately label gel electrophoresis images. No installation required—runs directly in your browser. Supports batch labeling, reference ladder comparison, and multiple export formats.

## 主要功能 / Key Features

- **双语支持 (Bilingual)**: 一键切换中文/英文界面 (Switch between Chinese and English).
- **智能标记 (Smart Labeling)**:
    - **单点标记 (Manual)**: 点击任意位置添加标记。
    - **批量行生成 (Batch Row)**: 快速生成一整排孔道标记 (1, 2, 3... 或 A, B, C...)。
    - **多种序列 (Sequences)**: 支持数字递增 (1, 2...) 和字母递增 (A, B... AA...)。
- **参考对比 (Reference Ladder)**:
    - 支持加载标准 Ladder 图片悬浮对比。
    - 可调节透明度、自由拖拽位置。
- **便捷操作 (Easy Operation)**:
    - **剪贴板支持 (Clipboard)**: 直接 `Ctrl+V` 粘贴图片（第一张为主图，第二张为参考图）。
    - **视图缩放 (Zoom)**: 10% - 300% 自由缩放。
    - **快捷键 (Shortcuts)**: 数字键切换工具，ESC 取消操作，Ctrl+Z 撤销。
- **数据管理 (Data Management)**:
    - 保存/加载工程文件 (.json) 以便日后继续编辑。
    - 导出标记后的图片 (.png)。

## 使用说明 / Usage

1. **加载图片**: 点击“打开图片”或直接 **Ctrl+V** 粘贴截图。
2. **选择工具**:
    - 按 `1`: 单点标记
    - 按 `2`: 批量行生成 (拖拽一条线，输入孔数)
    - 按 `3`: 移动调整
    - 按 `4`: 删除标记
3. **添加参考图**: 点击“加载 Ladder 图片”或在已有底图的情况下再次 **Ctrl+V** 粘贴。
4. **导出**: 完成后点击“导出结果”保存图片，或“保存工程”留底。

## 快捷键 / Shortcuts

| Key | Action |
| --- | --- |
| `1` | Manual Label (单点标记) |
| `2` | Batch Row (批量行生成) |
| `3` | Move Tool (移动工具) |
| `4` | Delete Tool (删除工具) |
| `ESC` | Cancel Operation (取消当前操作) |
| `Ctrl+Z` | Undo (撤销) |
| `Ctrl+Y` | Redo (重做) |
| `Ctrl+V` | Paste Image (粘贴图片) |

## License
MIT
