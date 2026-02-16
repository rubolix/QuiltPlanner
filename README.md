# QuiltPlanner 🧵

A comprehensive web-based quilt fabric calculator and layout planner. Plan your quilt, calculate yardage, visualize cutting layouts, and generate shopping lists — all in one free tool.

**👉 [Try it now](https://rubolix.github.io/QuiltPlanner/)**

## Features

### 📐 Quilt Layout
- **Size presets** — Baby, Throw, Twin, Full, Queen, King, or custom dimensions
- **Straight set & on-point (diagonal)** layouts with setting/corner triangles
- **Sashing, borders, binding** — configurable widths and fabric colors
- **Alternating blocks** — A/B checkerboard pattern with separate block definitions
- **Block arrangement** — Uniform, rotate 90°/180°, pinwheel, mirror horizontal/vertical
- **Smart suggestions** — Layout fit advice when blocks don't match target size

### 🧩 Block Designer
- **7 piece types** — Square, Rectangle, HST, QST, Flying Geese, Strip Set, Appliqué Circle
- **Up to 8 fabrics** with named colors and visual swatches
- **Piece type preview** — Visual diagram of each piece shape
- **Edit & reorder** pieces after adding
- **Alternating blocks** — Define separate pieces for Block A and Block B
- **🎲 Randomize Colors** to try new colorways

### 📊 Yardage Calculator
- **Per-fabric yardage** with cut sizes, strips needed, and waste margin
- **Sashing, border, binding, backing, batting** calculations
- **Pieced backing** — Horizontal vs vertical seam comparison when wider than WOF
- **Pre-wash shrinkage** — Optional +3% adjustment
- **Thread calculator** — Piecing and quilting thread estimates with spool count

### ✂️ Cutting & Visualization
- **Cutting instructions** — Detailed per-fabric cut list with sizes and strip counts
- **Cutting layout diagrams** — Canvas rendering of pieces packed into WOF strips
- **Repeat badges** — Identical strips consolidated with ×N count
- **Quilt preview** — Full visual with blocks, sashing, borders, and dimensions
- **Block preview** — Enlarged view of a single block's internal structure

### 💰 Shopping & Planning
- **Shopping list** — Consolidated yardage per fabric, rounded to nearest ⅛ yard
- **Cost estimator** — Per-fabric price inputs with grand total
- **Fabric stash tracker** — Save what you own (localStorage), see have vs. need
- **Precut compatibility** — Check if pieces fit Charm Packs, Layer Cakes, Jelly Rolls, Fat Quarters
- **🎨 Extract palette from photo** — Upload an inspiration image, extract dominant colors

### 🖨️ Output
- **Print / PDF** — Clean print layout with selectable sections
- **Coloring page** — Export black line-art quilt layout for hand coloring
- **JSON import/export** — Save and load full projects
- **CSV import/export** — Piece lists for sharing

### 🎯 Examples
13 built-in example projects: Nine Patch, Pinwheel, Sawtooth Star, Rail Fence, Log Cabin, Irish Chain, Bow Tie, Churn Dash, Bear's Paw, Ohio Star, Kaleidoscope (QST), Strip Garden, Modern Appliqué

## How to Use

1. Set your quilt dimensions (or pick a preset)
2. Choose layout style (straight or on-point) and block arrangement
3. Add pieces to your block — squares, rectangles, HSTs, flying geese, etc.
4. Click **⚡ Calculate Yardage**
5. Review the quilt preview, yardage, cutting layouts, and shopping list
6. Print, export, or save your project

## Quilting Math

- **Seam allowance** — Default ¼″, configurable
- **HST** — Cut squares ⅞″ larger than finished size, cut ╲ for 2 triangles
- **QST** — Cut squares 1¼″ larger, cut ╳ for 4 quarter-triangles
- **Flying Geese** — No-waste method: large square +1¼″ (yields 4), small squares +⅞″
- **Binding** — Strips at specified width across WOF, joined for perimeter + 12″
- **Backing** — Quilt size + 8″, with pieced panel options when wider than WOF
- **Batting** — Same dimensions as backing
- **On-point triangles** — Setting: block × √2 + 1¼″; Corner: block / √2 + ⅞″
- **Yardage** — Rounded up to nearest ⅛ yard, with optional waste margin and shrinkage

## Tech

- Single HTML file, all CSS and JS inline
- Zero dependencies, works offline
- Canvas-based rendering for all diagrams
- localStorage for fabric stash persistence

## License

MIT — free to use, modify, and share.
