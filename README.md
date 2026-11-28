# M920 · Renaissance

Ward-Beck Systems M920, 1994|27. Wiki page: [M920 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.RENAISSANCE.M920/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 10 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 8 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 3 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 6 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 18 |

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M920.kicad_sym](KICAD/M920.kicad_sym)
- [PCB M920-1 - M920](KICAD/PCB%20M920-1%20-%20M920)
- [PCB M920-2 - M920](KICAD/PCB%20M920-2%20-%20M920)
- [PCB M920TMP - M920](KICAD/PCB%20M920TMP%20-%20M920)
- [PCB M920WORK - M920](KICAD/PCB%20M920WORK%20-%20M920)
- [PCB M920WRK - M920](KICAD/PCB%20M920WRK%20-%20M920)

## Software

- [1994 - M920 - #ESP_OUT.txt](SOFTWARE/1994%20-%20M920%20-%20%23ESP_OUT.txt)

## 3-D model

[`MECHANICAL/M920.stl`](MECHANICAL/M920.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M920)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M920 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M920.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
