# PDF AutoMapper Pro

Visual PDF form automation tool with drag-and-drop field mapping and modern UI.

## ✨ Features

- **Visual Field Mapping** - Draw boxes directly on PDF templates with intuitive interface
- **Smooth Pan & Zoom** - Navigate large PDFs effortlessly with Space+Drag or scroll wheel
- **Smart Text Fitting** - Auto-adjusts font size and wraps text to fit perfectly
- **Calibration System** - Fine-tune text placement with pixel-perfect accuracy
- **Template Reusability** - Save field mappings for reuse across sessions
- **Multi-Select Operations** - Select, move, copy, or delete multiple fields at once
- **Context Menu** - Right-click for quick access to field operations
- **Move & Copy Fields** - Drag to move, Shift+Drag to copy fields
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
3. **Adjust Position** - Drag to move, Shift+Drag to copy, or use arrow keys
4. **Calibrate (Optional)** - Click "🎯 Calibrate" to fine-tune text placement
5. **Fill Data** - Click "✨ Fill" to enter your data with alignment options
6. **Preview & Adjust** - Review in preview mode, adjust font sizes if needed
7. **Generate PDF** - Click "Generate PDF" to create your filled document

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| **Arrow Keys** | Move selected fields (1px) |
| **Ctrl + Arrows** | Move fields faster (10px) |
| **Shift + Arrows** | Resize selected fields |
| **Ctrl + Click** | Multi-select fields (add/remove from selection) |
| **Double Click** | Rename field |
| **Delete / Backspace** | Delete selected field(s) |
| **Space + Drag** | Pan/move around PDF (smooth scrolling) |
| **Scroll Wheel** | Zoom in/out |
| **ESC** | Clear selection |

## 🖱️ Mouse Controls

### Navigation
- **Space + Left Click + Drag** - Smooth panning (recommended)
- **Middle Click + Drag** - Pan with scroll wheel button
- **Scroll Wheel** - Zoom in/out centered on cursor

### Field Operations
- **Click + Drag** - Draw new field box
- **Click on Field** - Select field
- **Drag Field** - Move field to new position
- **Shift + Drag Field** - Copy field to new position
- **Ctrl + Click** - Add/remove from multi-selection
- **Double Click** - Rename field
- **Right Click** - Open context menu

### Context Menu (Right-Click)
- **🗑️ Delete** - Remove selected field(s)
- **✏️ Rename** - Rename single field
- **📋 Duplicate** - Copy selected field(s) with offset
- **✅ Select All** - Select all fields at once
- **❌ Clear Selection** - Deselect all fields

## 🎯 Calibration System

Fine-tune text placement for pixel-perfect accuracy:

### When to Use Calibration
- Text appears slightly off from where you drew boxes
- Text touches edges of boxes
- Different PDF types need different positioning

### How to Calibrate
1. Click **🎯 Calibrate** button
2. Adjust **X Offset** slider (move text left/right)
3. Adjust **Y Offset** slider (move text up/down)
4. Set **Padding** values (space from edges)
5. Enter test text and click **Preview on Canvas**
6. See green preview on first field
7. Adjust until perfect
8. Click **Save Calibration**

### Calibration Settings
- **X Offset**: -20 to +20 pixels (horizontal adjustment)
- **Y Offset**: -20 to +20 pixels (vertical adjustment)
- **Padding**: 0-10 pixels (left, right, top, bottom)
- **Auto-save**: Settings saved per template
- **Auto-load**: Loads automatically when opening template

## 🎨 UI Features

- **Modern Dark Theme** - Easy on the eyes for long sessions
- **Color-Coded Buttons** - Intuitive action identification
- **Real-time Field Count** - Badge showing number of defined fields
- **Status Indicators** - Visual feedback for all operations
- **Custom Title Bar** - Borderless window with modern controls
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
3. **Multi-Select Power** - Hold Ctrl and click multiple fields to move/copy them together
4. **Shift to Copy** - Hold Shift while dragging to duplicate fields
5. **Right-Click Menu** - Quick access to all field operations
6. **Delete Key** - Fastest way to remove unwanted fields
7. **Calibrate Once** - Set calibration per template, never adjust again
8. **Preview Mode** - Always preview before generating to check font sizes
9. **Keyboard Shortcuts** - Use arrow keys for pixel-perfect positioning
10. **Auto-Save** - Field definitions are automatically saved per template

## 🎯 Advanced Features

### Multi-Select Operations
- **Select Multiple**: Ctrl+Click on fields
- **Select All**: Right-click → Select All
- **Move Together**: Drag any selected field to move all
- **Copy Together**: Shift+Drag to copy all selected fields
- **Delete Together**: Press Delete to remove all selected
- **Resize Together**: Shift+Arrows to resize all selected

### Field Management
- **Move Field**: Click and drag to new position
- **Copy Field**: Hold Shift and drag to duplicate
- **Rename Field**: Double-click or right-click → Rename
- **Delete Field**: Select and press Delete key
- **Duplicate Field**: Right-click → Duplicate (20px offset)

### Text Alignment
- **Horizontal**: Left, Center, Right
- **Vertical**: Top, Middle, Bottom
- **Custom Padding**: Control space from edges
- **Auto Font Sizing**: Automatically finds best font size
- **Text Wrapping**: Smart word wrapping for long text

### Template Persistence
- **Field Mappings**: Saved in `pdf_filler_config.json`
- **Calibration Settings**: Saved per template
- **Auto-Load**: Automatically loads when opening template
- **Export Code**: Export field definitions as Python code

## 📝 Version History

- **v2.1** - Added move/copy modes, context menu, delete functionality, calibration system
- **v2.0** - Modern UI overhaul, smooth pan functionality, improved UX
- **v1.1** - Multi-select, keyboard controls, live preview
- **v1.0** - Initial release with basic field mapping

## 👨‍💻 Created By

**ENODD** - PDF AutoMapper Pro

---