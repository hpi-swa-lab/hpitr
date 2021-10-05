hpitr
=====
  Copyright (c) Tobias Pape <tobias.pape at hpi.uni-potsdam.de>
  2021/10/05 v2.1

  A unified class for Technical Reports at the HPI

This constitutes the  class to create technical reports at the
Hasso Plattner Institute, Potsdam in conjunction with the Universitätsverlag
Potsdam. To maintain a unified appearance, this class provides macrotypographic
(like paper size and general layout) and microtypographic (like fonts and their
adjustment) settings.

 ---

Diese Klasse dient zur Erstellung von technischen Berichten
am Hasso-Plattner-Institut, Potsdam, in Zusammenarbeit mit dem
Universitätsverlag Potsdam. Zur Erhaltung eines einheitlichen
Erscheinungsbildes bietet diese Klasse Einstellungen zu Makrotypographie (wie
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
<https://github.com/hpi-swa-lab/hpitr/releases>
