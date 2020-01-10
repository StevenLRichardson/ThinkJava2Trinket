# ThinkJava2Trinket
LaTeX source for an Adapted/Augmented version of _Think Java 2_ by Chris Mayfield and Allen Downey.  Their work, Copyright (c) 2019, is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.  See http://greenteapress.com/wp/think-java-2e/.

Copyright (c) 2020 Steven L. Richardson. This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.  Readers are free to copy and distribute the text, and are also free to modify it provided they cite the original authors, use it only for non-commercial purposes, and apply the same Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License to their work.

This is a work in progress. Expected completion is Spring 2020.

Build scripts and trinket hosting provided by Elliott Hauser of Trinket.io. See https://trinket.io/.  Scripts and/or supporting files modified and used under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

The Makefile will build pdf, html, or trinket-html versions of the text.  The author has adapted the original work for use in an online class, intended as an html-based trail through the material supported with inline trinkets and inline exercises for readers to investigate via the trinkets.  As such, the pdf and (non-trinket) html versions of this text are not useful as they would refer the reader to absent trinkets.

To build the trinket-html version of the text, invoke the Makefile as follows:
<p><code>
  make trinket
</code>

This requires the hevea package.  You may also need to install texlive-latex-extra and texlive-fonts-recommended.
