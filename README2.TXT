From news.duc.auburn.edu!darwin.sura.net!haven.umd.edu!uunet!math.fu-berlin.de!unidus.rz.uni-duesseldorf.de!sowa.rz.uni-duesseldorf.de!sowa Mon Jan 25 19:50:00 CST 1993
Article: 8776 of comp.text.tex
Path: news.duc.auburn.edu!darwin.sura.net!haven.umd.edu!uunet!math.fu-berlin.de!unidus.rz.uni-duesseldorf.de!sowa.rz.uni-duesseldorf.de!sowa
From: sowa@convex.rz.uni-duesseldorf.de (Friedhelm Sowa)
Newsgroups: comp.text.tex
Subject: bm2font 2.0
Date: Mon, 25 Jan 1993 15:02:21 GMT
Organization: URZ Heinrich-Heine-Universitaet
Lines: 23
Message-ID: <sowa.11.727974141@convex.rz.uni-duesseldorf.de>
NNTP-Posting-Host: sowa.rz.uni-duesseldorf.de
Keywords: bitmaps,halftones,graphics

Within the next few hours bm2font version 2.0 will be available
from the stuttgart server (ftp.uni-stuttgart.de).
In case of emergency you can get it out of the darkness of the 
incoming subdirectory there.
 
The new version does not support the pixel file format any more.
So the pk files can grow up to 64KB now :-) and bm2font generates
much less fonts for one picture. In case of two colors (black and white)
the picture may fit into one font, depending on the resolution of course.

The -p parameter now has a different meaning: it controls the
size of the generated characters. Default is width and height up
to one inch, with -pn the limit is 0.5 inch, more characters and
more fonts. If you have problems with the default size (LN03?)
try -pn.
 
Thanks to all who have been waiting for the new version for such
a long time.
 
I hope the C-version will follow soon.

Regards
Friedhelm Sowa


