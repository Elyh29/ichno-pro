# Ichno PRO release notes

## 1.0.4 (2026-11-08)
Includes everything in Ichno 1.0.6 (section views, cutting planes page, coloured planes, ISO 2768 tolerances with a table of deviations, ISO small dimensions, F1 help, SVG layers), plus:
- Custom BOM columns (Bill of Materials panel): up to 5 columns between Part and Qty, on the drawing, in the annex and in the CSV / Excel files: material, size, collection, position (axis and reference point) or any custom property of the objects (supplier, reference…); editable title, adjustable order
- Section views in DXF: hatching on its own HATCH layer, at real size 1:1; the cutting planes page is one more DXF sheet
- Balloons: in a column left or right of the view, or in a row above or below it (a long view such as a fuselage takes a row), on one to three staggered rows when there are many; they stay in the frame, avoid the other views, the title block and the dimensions, and their leaders hardly ever cross
- Balloons: Straight Leaders option, each balloon in line with its part; an info line warns when the parts are too close
- Balloons: on the front, side and top views the leader starts from the centre of the part; on the isometric view, from a visible point of it
- Manual vertical dimensions: room reserved left of the view, their value no longer leaves the frame
- Title block templates: tolerance classes, envelope (E) and table of deviations saved; templates from earlier versions (“ISO 2768-mK”) are read
- Online Manual (F1) on a PRO setting opens its page of the [Ichno PRO wiki](https://github.com/Elyh29/ichno-pro/wiki)

## 1.0.3 (November 1, 2026)
Includes everything in Ichno 1.0.5 (ISO / ASME standards, ISO 128 line weights, ISO 5457 border and filing margin, Checked / Approved / Tolerances / Material in the title block, bill of materials on a separate sheet, reorganized panel), plus:
- Panel reorganized like the free edition: DXF in Output, CSV / Excel and balloons in Bill of Materials
- Balloons: 5 mm numbers in a 10 mm circle (ISO 6433), placed left of the view when the height dimension is on the right
- Title block templates now save the standard, filing margin, view titles, Checked, Approved, Tolerances and Material
- DXF: the bill of materials annex is exported as an extra DXF sheet; CSV / Excel count each row only once

## 1.0.2 (November 1, 2026)
- Bill of materials: choose the collections that are counted (all when the list is empty); balloons and CSV / Excel follow this choice
- Sheets per collection: choose which sheets show the bill of materials

## 1.0.1 (November 1, 2026)
- Balloons: each leader ends on a visible part of its object, no longer on its centre, which was sometimes hidden

## 1.0.0 (November 1, 2026)
First release. Includes everything in Ichno 1.0.4, plus:
- DXF export: one sheet per file (AutoCAD R12), layers VISIBLE, HIDDEN (dashed), DIMENSIONS, TEXT, FRAME, declared in millimetres
- DXF at real size (1:1, default): the views measure their true dimensions in a CAD tool; otherwise paper millimetres
- Bill of materials to CSV and Excel (.xlsx): headers in the drawing language, total row, Sheet column when there are several sheets
- Title block templates: company, logo, author, ownership notice, custom fields, legend and sheet settings saved under a name; export / import as JSON with the logo included
- Batch export: every scene of the file, or every .blend of a folder, one drawing each with its own settings; cancellable
- Balloons: one number per bill of materials row, linked to its largest object, on the chosen view
- Manual dimensions: between 2 vertices (Edit Mode) or 2 positions of the 3D cursor; Auto view (true length) or Front / Side / Top
- Replaces the free edition: only one edition of Ichno is active at a time
