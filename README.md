hpitr
  Copyright (c) Tobias Pape <tobias.pape at hpi.uni-potsdam.de>
  2017/03/03 v1.5
  A unified class for Technical Reports at the HPI

This consititutes the LaTeX class to creat technical reports at the
Plattner Institute, Potsdam in conjunction with the Universitätsverlag
Potsdam. To maintain a unified appearance, this class provides macrotypographic
(like paper size and general layout) and microtypographic (like fonts and their
adjustment) settings.

 ---

Diese LaTeX-Klasse dient zur Erstellung von technischen Berichten
am Hasso-Plattner-Institut, Potsdam, in Zusammenarbeit mit dem
Universitätsverlag Potsdam. Zur Erhaltung eines einheitlichen
Erscheinungsbildes bietet diese Klasses Einstellungen zu Makrotypographie (wie
Papiergröße, allgemeines Layout) und auch zur Detailtypographie (wie
Schriftwahl).


-------------------------------------------------------------------------------
Note: To generate all files, you should simply call

    pdftex -shell-escape hpitr.dtx

If you are using MiKTeX you have to use

    pdftex --enable-write18 hpitr.dtx

to fully enable shell escapes which are also known as \write18 feature.

All ltx files should be installed together with all pdf files at documentation
folder. The sty file together with all def files should be installed at latex
package folder.

But maybe your distributor already distributes a ready for installation
package, so you do not need to create files and copy them yourself.

-------------------------------------------------------------------------------

Prepared files (class, documentation) are available for releases at
<https://github.com/HPI-SWA-Lab/hpitr/releases>
