## Independent JPEG Group: JPEG release 6b

### JPEG License
<pre>

Must reproduce following license in documentation and/or other materials
provided with distribution:

The authors make NO WARRANTY or representation, either express or implied,
with respect to this software, its quality, accuracy, merchantability, or
fitness for a particular purpose.  This software is provided "AS IS",
and you, its user, assume the entire risk as to its quality and accuracy.

This software is copyright (C) 1991-1998, Thomas G. Lane.
All Rights Reserved except as specified below.

Permission is hereby granted to use, copy, modify, and distribute
this software (or portions thereof) for any purpose, without fee,
subject to these conditions:

(1) If any part of the source code for this software is distributed,
then this README file must be included, with this copyright and no-warranty
notice unaltered; and any additions, deletions, or changes to the original
files must be clearly indicated in accompanying documentation.

(2) If only executable code is distributed, then the accompanying documentation
must state that "this software is based in part on the work of the
Independent JPEG Group".

(3) Permission for use of this software is granted only if the user accepts
full responsibility for any undesirable consequences; the authors accept
NO LIABILITY for damages of any kind.

These conditions apply to any software derived from or based on the IJG code,
not just to the unmodified library.  If you use our work, you ought to
acknowledge us.

Permission is NOT granted for the use of any IJG author's name or company name
in advertising or publicity relating to this software or products derived
from it.  This software may be referred to only as "the Independent JPEG
Group's software".

We specifically permit and encourage the use of this software as the basis
of commercial products, provided that all warranty or liability claims are
assumed by the product vendor.


ansi2knr.c is included in this distribution by permission of L. Peter Deutsch,
sole proprietor of its copyright holder, Aladdin Enterprises of Menlo Park, CA.
ansi2knr.c is NOT covered by the above copyright and conditions, but instead
by the usual distribution terms of the Free Software Foundation; principally,
that you must include source code if you redistribute it.
(See the file ansi2knr.c for full details.)  However, since ansi2knr.c is
not needed as part of any program generated from the IJG code, this does not
limit you more than the foregoing paragraphs do.

The Unix configuration script "configure" was produced with GNU Autoconf.
It is copyright by the Free Software Foundation but is freely distributable.
The same holds for its supporting scripts (config.guess, config.sub,
ltconfig, ltmain.sh).  Another support script, install-sh, is copyright
by M.I.T. but is also freely distributable.

It appears that the arithmetic coding option of the JPEG spec is covered
by patents owned by IBM, AT&T, and Mitsubishi.  Hence arithmetic coding
cannot legally be used without obtaining one or more licenses.  For this
reason, support for arithmetic coding has been removed from the free
JPEG software. (Since arithmetic coding provides only a marginal gain
over the unpatented Huffman mode, it is unlikely that very many
implementations will support it.) So far as we are aware, there are
no patent restrictions on the remaining code.

The IJG distribution formerly included code to read and write GIF files.
To avoid entanglement with the Unisys LZW patent, GIF reading support
has been removed altogether, and the GIF writer has been simplified to
produce "uncompressed GIFs".  This technique does not use the LZW algorithm;
the resulting GIF files are larger than usual, but are readable by all
standard GIF decoders.

We are required to state that "The Graphics Interchange Format(c) is
the Copyright property of CompuServe Incorporated.  GIF(sm) is a
Service Mark property of CompuServe Incorporated."

</pre>