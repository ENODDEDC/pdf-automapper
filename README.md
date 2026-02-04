# PDF AutoMapper Pro

Visual PDF form automation tool with drag-and-drop field mapping and modern UI.

## ✨ Features

- **Visual Field Mapping** - Draw boxes directly on PDF templates with intuitive interface
- **Smooth Pan & Zoom** - Navigate large PDFs effortlessly with Space+Drag or scroll wheel
- **Smart Text Fitting** - Auto-adjusts font size and wraps text to fit perfectly
- **Template Reusability** - Save field mappings for reuse across sessions
- **Multi-Select** - Copy multiple fields at once with Ctrl+Click
- **Keyboard Controls** - Precise positioning with arrow keys
- **Live Preview** - See results before generating PDF with adjustable font sizes
- **Modern UI** - Professional desktop-grade interface with dark theme

## 🖼️ Screenshots

*Version 2.0*
![Demo](screenshots/Version%202.0.png)
*Demo - Work in Progress*

## 🚀 Quick Start

1. **Load PDF Template** - Click "📁 Template" button or use welcome screen
2. **Draw Field Boxes** - Click and drag on PDF to create field areas
3. **Adjust Position** - Use arrow keys or drag fields to fine-tune placement
4. **Fill Data** - Click "✨ Fill" to enter your data with alignment options
5. **Preview & Adjust** - Review in preview mode, adjust font sizes if needed
6. **Generate PDF** - Click "Generate PDF" to create your filled document

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| **Arrow Keys** | Move selected fields (1px) |
| **Ctrl + Arrows** | Move fields faster (10px) |
| **Shift + Arrows** | Resize selected fields |
| **Ctrl + Click** | Multi-select fields |
| **Double Click** | Rename field |
| **Space + Drag** | Pan/move around PDF (smooth scrolling) |
| **Right Click + Drag** | Alternative pan method |
| **Middle Click + Drag** | Another pan option |
| **Scroll Wheel** | Zoom in/out |
| **ESC** | Clear selection |

## 🖱️ Mouse Controls

### Navigation
- **Space + Left Click + Drag** - Smooth panning (recommended)
- **Right Click + Drag** - Quick pan
- **Middle Click + Drag** - Pan with scroll wheel button
- **Scroll Wheel** - Zoom in/out centered on cursor

### Field Operations
- **Click + Drag** - Draw new field box
- **Click on Field** - Select field
- **Ctrl + Click** - Add/remove from multi-selection
- **Double Click** - Rename field
- **Drag Selected Field** - Copy field to new position

## 🎨 UI Features

- **Modern Dark Theme** - Easy on the eyes for long sessions
- **Color-Coded Buttons** - Intuitive action identification
- **Real-time Field Count** - Badge showing number of defined fields
- **Status Indicators** - Visual feedback for all operations
- **Collapsible Panels** - Maximize workspace when needed
- **Smooth Animations** - Professional feel with hover effects

## 🛠️ Built With

- **Python 3.8+**
- **CustomTkinter** - Modern UI framework
- **PyMuPDF (fitz)** - PDF rendering
- **PyPDF** - PDF manipulation
- **ReportLab** - PDF generation
- **Pillow (PIL)** - Image processing

## 📋 Requirements

```bash
pip install customtkinter pymupdf pypdf reportlab pillow
```

## 💡 Tips & Tricks

1. **Zoom First** - Zoom in for precise field placement
2. **Use Space+Drag** - Smoothest way to navigate large PDFs
3. **Multi-Select** - Hold Ctrl and click multiple fields to copy them together
4. **Preview Mode** - Always preview before generating to check font sizes
5. **Keyboard Shortcuts** - Use arrow keys for pixel-perfect positioning
6. **Auto-Save** - Field definitions are automatically saved per template

## 🎯 Advanced Features

- **Field Copying** - Drag selected fields to duplicate with same dimensions
- **Batch Operations** - Multi-select and move/resize multiple fields at once
- **Font Auto-Sizing** - Automatically finds best font size in preview
- **Text Alignment** - Choose horizontal (left/center/right) and vertical (top/middle/bottom)
- **Template Persistence** - Field mappings saved in `pdf_filler_config.json`

## 📝 Version History

- **v2.0** - Modern UI overhaul, smooth pan functionality, improved UX
- **v1.1** - Multi-select, keyboard controls, live preview
- **v1.0** - Initial release with basic field mapping