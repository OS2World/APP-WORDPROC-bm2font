This is the documentation for Sowa's BitMapTOfont program. Currently, 
bm2font is 2.0, but the documentation is still 1.1. See the notes in the
program archive bm2fon20.zip. (bm2fon20.zip contains OS/2 2.x and MSDOS
executables.) Files:
  bm2fman.dvi   Documentation in German
  bm2fmane.dvi  English translation

bm2font can convert graphics files (such as GIF) to PK files for use with
TeX. In order to print the manual, the driver must be able to find the pk
files. The method is driver-dependent. 

Example: The emTeX drivers usually use a configuration file ".cnf". One 
can modify the "/pf" line to include a search of the current directory for
pk files.

3 March 1993

=============================================================================
The following notes may no longer apply. They were collected when the
English version of the manual was released.

From: ecsgrt@luxor.latrobe.edu.au (Geoffrey Tobin)
Subject: BM2FONT English manual - found and printed.
Date: 27 Oct 92 10:37:50 GMT


The long-sought English version of Friedhelm Sowa's "BM2FONT Users
Manual" is indeed available, in at least this location:

    vogon.mathi.uni-heidelberg.de :
    /Sources/TeX/Contrib/grafix/bm2font/bm2fmane.dvi

(Note the 4 uppercase letters.)

The date on the file "bm2fmane.dvi" is "26 May 1992", the same as the
copy there of the German original.

In order to print the manual, one also needs all the *.pk and *.tfm
files.

On a unix system, I found it necessary to rename all the *.pk files to
*.300pk, in order for "dvips" to recognise them.  This may not be
necessary on a PC using emTeX's file hierarchy.

The PostScript form of the manual uses 2 or 3 Megabytes, depending on
whether dvips's bitmap compression option "-Z" is used.  So I prepared
it 5 or 10 pages at a time, to keep each piece comfortably under 1 MB.
This advice came from Norman Walsh (walsh@cs.umass.edu).
The page numbers run:  1-4, 1-33.

The English version is slightly expanded over the German edition, with
an early explanation of how to use BM2FONT to put the picture of
Donald Duck on the cover into PK form.

As a reminder, non-PC versions of BM2FONT are available in the
"bm2fontC" (watch the Capital "C") subdirectory of "grafix".

The "testpix" subdirectory of "bm2fontC" contains the originals of
many pictures used in the manual, and other graphics, for developers
and beta testers to try out their port of BM2FONT on.  Warning:  some
of the astronomy pictures, for instance, are over 1 megabyte each!

Also, on page 33, this address is given for the maintenance of the
English language edition (the punctuation is not given, so the line
divisions are only my guess):

    Bart Childs
    Department of Computer Science
    Texas A&M University
    College Station TX
    USA
    77843-3112
    Telephone:  409 845-5470
    Telefax:    409 847-8578
    Email:  bart@cs.tamu.edu
       or:  bart@tamzeus.bitnet

For the German original, Friedhelm Sowa's email contact address is
given as:

    Friedhelm Sowa
    Email:  tex@ze8.convex.rz.uni-duesseldorf.de
       or:  sowa@convex.rz.uni-duesseldorf.de


All the Best!
Geoffrey Tobin    ecsgrt@luxor.latrobe.edu.au


=============================================================================
From: ecsgrt@luxor.latrobe.edu.au (Geoffrey Tobin)
Newsgroups: comp.text.tex
Subject: Re: BM2Font sources
Date: 26 Oct 92 07:10:16 GMT


This is posted because the questioner's address is not accessible to
me, and I understand that others are interested.

Petr Novotny wrote:

>Some time ago I've read on this list that there are BM2Font sources in C
>available to anonymous FTP.

Once upon a time, I posted mention of the BM2FONT sources in C.

>The address written there was vogon.mathi.uni-heidelberg.de.

Yes.

>Unfortunately, on that FTP site I cannot find the directory specified
>in that post.

Well, perhaps a typo occurred, because I just went there:

    ftp  vogon.mathi.uni-heidelberg.de
    cd   /Sources/TeX/Contrib/grafix/

and I saw, with the date of Sep 22, this directory:

    bm2fontC

>There was also a remark in that post that after some time, the sources will
>be in all good archives. A week ago I've tried RUSVM1 at Stuttgart, today
>I've just tried Claremont - I couldn't find it there ...

Agreed.  That suggests that bm2font, C version, is still in beta test.

It's been ported to NeXT, IBM RS/6000, and Sparc.

Mahilata's Vogon site is a NeXT.  Also, I've compiled bm2font on an
RS/6000 and on a Sparc 1, but at that time the testpix were not
available.  So I recommend that anyone who wishes to test bm2font in
C, should try it out on the files in:

    /Sources/TeX/Contrib/grafix/bm2fontC/testpix

Last I heard, the manual had still not been translated into English.
Anyone willing to undertake that task?  The little I've understood of
the German manual is in quite good humor.

Geoffrey Tobin    ecsgrt@luxor.latrobe.edu.au


=============================================================================
From: gt@ee.latrobe.edu.au (Geoff Tobin)
Newsgroups: comp.text.tex
Subject: BM2FONT Web sources - location.
Date: 28 Oct 92 05:58:14 GMT


On 9 September, I inquired of archie about "bm2font".  It mentioned
Bart Childs' site, where the TeX source for the English manual, and
a Web source for bm2font (I presume for IBM-PCs) are found.

Geoffrey Tobin    ecsgrt@luxor.latrobe.edu.au

PS:  Bart Childs is at  bart@cs.tamu.edu  or  bart@tamzeus.bitnet


Host csseq.cs.tamu.edu

    Location: /web
      DIRECTORY drwxr-xr-x       3072  May 19 21:05  bm2font
    Location: /web/bm2font
           FILE -rwxr-xr-x       1172  Feb 24 07:19  bm2font.cdl
           FILE -rwxr-xr-x      73376  Dec 17 1991  bm2font.exe
           FILE -rwxr-xr-x      67984  Feb 24 07:19  bm2font.exe.1.0
           FILE -rwxr-xr-x      73008  Feb 24 07:19  bm2font.exe.1.1a
           FILE -rwxr-xr-x     128354  Feb 24 07:19  bm2font.web
           FILE -rwxr-xr-x       6374  Dec 17 1991  bm2fonte.aux
           FILE -rwxr-xr-x      48830  Apr  8 09:28  bm2fonte.tex

