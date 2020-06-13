# ThinkJava2Trinket
LaTeX source for an Adapted/Augmented version of _Think Java 2_ by Chris Mayfield and Allen Downey.  Their work, Copyright (c) 2019, is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.  See http://greenteapress.com/wp/think-java-2e/.

Copyright (c) 2020 Steven L. Richardson. This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.  Readers are free to copy and distribute the text, and are also free to modify it provided they cite the original authors, use it only for non-commercial purposes, and apply the same Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License to their work.

This work is sourced from two different versions of the original work by Chris Mayfield and Allen Downey.  Chapters 1 through 7 are modifications to version 6. Said modifications were completed in August, 2019.  In Fall of 2019, the authors released their version 7 (draft) with many additional chapters, and the remaining chapters in this repo are modifications of that version. 

Build scripts and trinket hosting provided by Elliott Hauser of Trinket.io. See https://trinket.io/.  Scripts and/or supporting files have been modified and used under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.


The Makefile will build pdf, html, or trinket-html versions of the text.  The author has adapted the original work for use in an online class, intended as an html-based trail through the material supported with inline trinkets and inline exercises for readers to investigate via the trinkets.  As such, the pdf and (non-trinket) html versions of this text are not useful as they would refer the reader to absent trinkets. 


To build the trinket-html version of the text, invoke the Makefile as follows:
<p><code>
  make trinket
</code>

This requires the hevea package.  You may also need to install texlive-latex-extra and texlive-fonts-recommended.
