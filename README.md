# Vintage-Radio-KiCad-Symbols
Vacuum tube and passive components most commonly found in pre-transistor radios.

Primary goal is to create a set of symbol libraries that cover 99% of the components 
found in older tube radios such as the All American Fives (AA5) and others. The libraries 
should contain common items, even if already present in other standard libraries. Reduce 
the choices to create effeciency.

## This is a work in progress
No guarantees are made for usability. These symbols were drawn in KiCad 8.0 and later.

## Design notes
All symbols should be drawn on 50.00 mils grid (Kicad default for all symbols).
All pins/connections must fall on this grid.

### Vacuum Tubes Notes
- Standard tube outline (circle) 400 mils anchored at 0,0.
- Always show index pin.
- DeMorgan Standard: should be in pin order.
- DeMorgan Alternate: should be grouped by workflow.
- Should show internal wiring of pin to element.
- For internal visual layout try to reference a manufacturer data sheet.

Symbol properties

- Reference value: V?
- Value: Tube identifier, such as "12SA7" or leave blank
- Description: Most common usage, such as "OSCILLATOR/MIXER" or leave blank
- Symbol name: same as value
- Keywords: common name for tube, such as "PENTAGRID CONVERTER, HEPTODE", could also
  contain other tube identifiers

---

Looking for collaborators, contact me. K4TFJ, good on QRZ and here.
