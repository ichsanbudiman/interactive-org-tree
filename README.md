# D3.js Interactive Organization Tree Chart

A powerful, interactive tree chart visualization built with D3.js for displaying organizational hierarchies. Features draggable nodes, editable links with control points (elbows), and export to PDF functionality.

## Features

### Editor Mode (`editor.html`)
- **Drag & Drop Nodes**: Reposition nodes by dragging them
- **Interactive Links**: Click on links to add control points (elbows) for custom routing
- **Editable Control Points**: Drag red control points to adjust link paths
- **Add Child Nodes**: Add new nodes (rectangle or table type) to any existing node
- **Edit Nodes**: 
  - Edit name and class for rectangle nodes
  - Edit table data for table nodes
- **Save & Load**: Save your graph as JSON and load it back
- **Auto Layout**: Automatic positioning for nodes without coordinates
- **Dynamic Canvas**: Canvas size adjusts based on graph bounds

### Preview Mode (`preview.html`)
- **View-Only Display**: Clean presentation mode without editing controls
- **PDF Export**: Export graph to PDF with customizable:
  - Paper size (A4, A3, A2, A1, A0, Letter, Legal, Tabloid)
  - Orientation (Portrait/Landscape)
  - Graph title/name
- **Proportional Scaling**: Graph scales proportionally to selected paper size
- **Load Graphs**: Load saved JSON files via drag & drop

## Files

- `editor.html` - Full-featured editor with drag, edit, and save functionality
- `preview.html` - View-only mode with PDF export capability

## Usage

### Editor Mode
1. Open `editor.html` in a web browser
2. Edit the graph by dragging nodes, adding/editing nodes, or adjusting link paths
3. Click "Save Graph" to download as JSON
4. Use drag & drop to load previously saved graphs

### Preview Mode
1. Open `preview.html` in a web browser
2. Load a JSON file via drag & drop
3. Click "Export to PDF" to generate a PDF with custom paper size and title

## License

This project is open source and available for use.

## Contributing

Feel free to fork, modify, and use this project for your needs.
