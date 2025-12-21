# Gel Labeler Pro (电泳胶孔标记工具专业版)

Gel Labeler Pro is a professional, web-based tool designed for labeling gel electrophoresis images. It supports batch labeling, reference ladder comparison, and bilingual (English/Chinese) interface.

## Features

- **Batch Labeling**: Quickly generate rows of numbered or lettered labels.
- **Reference Ladder**: Overlay a standard or custom ladder image for comparison.
- **Customization**: Support for numbers, letters, and custom text labels with adjustable fonts and colors.
- **Project Management**: Save your work as a project file and resume later.
- **Privacy Focused**: All processing happens locally in your browser. No images are uploaded to any server.

## User Guide (使用说明)

### 1. Getting Started (开始使用)
- **Load Image**: Click "Open Image" or drag & drop your gel image (JPG, PNG, TIF) onto the canvas. You can also paste an image directly using `Ctrl+V`.
- **Language**: Toggle between English and Chinese using the "EN/中文" button in the top right corner.

### 2. Tools (工具栏)

| Tool | Shortcut | Description |
|------|----------|-------------|
| **Manual Label** (单点标记) | `1` | Click anywhere to add a single label. Auto-increments numbers/letters. |
| **Batch Row** (批量行生成) | `2` | Click start point, then click end point. Enter the number of wells to generate evenly spaced labels. |
| **Move / Adjust** (移动调整) | `3` | Drag individual labels to fine-tune their position. |
| **Select / Edit** (框选编辑) | `4` | Click and drag to box-select multiple labels. Move them as a group, change their color, or copy/paste. |
| **Delete Label** (删除标记) | `5` | Click on any label to remove it. |

### 3. Label Options (标记选项)
- **Label Type**: 
  - **Number**: 1, 2, 3...
  - **Letter**: A, B, C...
  - **Custom**: Enter any text (e.g., "Ctrl", "Exp1").
- **Start Number**: Set the starting number or letter for the next label.
- **Style**: Choose between "Handwritten" or "Standard" font, adjust size, and pick colors.

### 4. Reference Ladder (参考 Ladder)
- **Load Standard Ladder**: Loads a built-in standard ladder image.
- **Load Custom Ladder**: Upload your own ladder image to overlay.
- **Adjust**: Drag the ladder panel to position it next to your bands. Use the slider to adjust opacity.

### 5. Shortcuts (快捷键)

- **Tools**: Keys `1` to `5` to switch tools.
- **Edit**:
  - `Ctrl + C` / `Cmd + C`: Copy selected labels.
  - `Ctrl + V` / `Cmd + V`: Paste labels.
  - `Delete` / `Backspace`: Delete selected labels.
- **History**:
  - `Ctrl + Z` / `Cmd + Z`: Undo.
  - `Ctrl + Y` / `Cmd + Y` (or `Shift + Ctrl + Z`): Redo.

### 6. Saving & Exporting (保存与导出)
- **Save Project**: Downloads a `.json` file containing your labels and settings. Use "Load Project" to restore your session later.
- **Export Result**: Downloads the final labeled image as a PNG file.

---

## Privacy
This tool runs entirely in your browser. Your images are **never** uploaded to any server.

## License
MIT License
