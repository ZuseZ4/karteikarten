# karteikarten

A really simple repo to create an anki deck based on a latex-beamer.pdf file.
Frametitles are cropped and used for the frontsides, 
following text is placed on the backside.


# Usage:
open pdf2anki and adjust the dst path to match your own anki installation

make pdf2anki executable (if necessary): chmod +x pdf2anki

call it:
./pdf2anki <yourscript>.pdf <scripttopic>

import created <scripttopic>_anki.txt file using anki (allowing html)
