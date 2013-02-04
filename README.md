StripRelocMod
=============

StripReloc that also removes the export section

This is modification of [StripReloc](http://www.jrsoftware.org/striprlc.php) with ability to strip out export section.
In some cases this can reduce size of exe-file on about 1MB.

When you use C++ builder with Delphi-compiled components, in export section appears some useless records.

There is software that can remove these records, (PE Corrector for example).
This is free alternative. [GPL license](http://www.gnu.org/copyleft/gpl.html)
