# 16n electronics

Electronics CAD and design for the 16n faderbank.

## VERSION

1.31

## Directory contents

* `16n.sch` and `16n.brd` are EAGLE 9.1.3 format schematic and board layout for the project.
* `16n_schematic.pdf` is the schematic in PDF format.
* `16n_v126.brd/sch` are **old, legacy layouts that are not recommended for use**. They are kept for historical reasons.
* `bom.csv` is a CSV rendition of a BOM for the project. The parts are all highly generic - any brand of 0805 resistors will do, for instance. For more specific recommendations, the [live BOM at Octopart][octobom] has links to specific components, designed around things easily purchased from Mouser, though note that stock of one manufacturer's parts may not be guaranteed, and you might need to edit your basket to find parts in stock.
* `gerbers` contains RS-274x format Gerber files for the current version of the board. These files are named per OSHpark standards, though OSHpark is an expensive place to make a 16n - you may wish to rename before you send them to another manufacturer. Do not assume your fab house can just make these - if your fab house has specific CAM rules, you should generate your own Gerbers from EAGLE.

---

[octobom]: https://octopart.com/bom-tool/unJxkzvR