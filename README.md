# awesome-z-machine

> A curated list of awesome things related to the z-machine, ZIL (Zork Implementation Language) programming, and Infocom.

The Z-machine is a virtual machine that was developed by Joel Berez and Marc Blank in 1979 and used by Infocom for its text adventure games. Infocom compiled game code to files containing Z-machine instructions (called story files or Z-code files) and could therefore port its text adventures to a new platform simply by writing a Z-machine implementation for that platform. With the large number of incompatible home computer systems in use at the time, this was an important advantage over using native code or developing a compiler for each system.

This tiny archive attempts to collect key z-machine documents.

## Z-Machine Overview

- https://en.wikipedia.org/wiki/Z-machine

  > The Z-machine is a virtual machine that was developed by Joel Berez and Marc Blank in 1979 and used by Infocom for its text adventure games. Infocom compiled game code to files containing Z-machine instructions (called story files or Z-code files) and could therefore port its text adventures to a new platform simply by writing a Z-machine implementation for that platform. With the large number of incompatible home computer systems in use at the time, this was an important advantage over using native code or developing a compiler for each system.

- [A Short History of the Z-machine](https://www.inform-fiction.org/zmachine/standards/z1point0/appd.html)

  > Infocom made six main Versions of the Z-machine and several minor variant forms. These are recognisably similar but with labyrinthine differences, like different archaic dialects of the same language. (The archaeological record stops sharply in 1989 when the civilisation in question collapsed.)

- [The Z-Machine Standards Document v1.1 // 24 Feb 2014](https://www.inform-fiction.org/zmachine/standards/z1point1/index.html)

  - [PDF Version](https://github.com/heasm66/z-machine-standards-document_1_1)

  > The Z-machine was created on a coffee table in Pittsburgh in 1979. It is an imaginary computer whose programs are adventure games, and is well-adapted to its task, implementing complex games remarkably compactly. They were still perhaps 100K long, too large for the memory of the home computers of their day, and the Z-machine seems to have made the first usage of virtual memory on a microcomputer. Further ahead of its time was the ability to efficiently save and restore the entire execution state.

- [Z-Machine // ifwiki.org](http://www.ifwiki.org/index.php/Z-machine)

  > The Z-machine is a virtual machine that was developed by Joel Berez and Marc Blank in 1979 and used by Infocom for its text adventure games. Infocom compiled game code to files containing Z-machine instructions (called story files, or Z-code files), and could therefore port all its text adventures to a new platform simply by writing a Z-machine implementation for that platform. With the large number of incompatible home computer systems in use at the time, this was an important advantage over using native code.

  > The compiler (called Zilch) which Infocom used to produce its story files has never been released, although documentation of the language used (called ZIL, for Zork Implementation Language) is still in existence.

  > The "Z" of Z-machine stands for Zork, Infocom's first adventure game. Z-code files usually have names ending in .z1, .z2, .z3, .z4, .z5, .z6, .z7 or .z8 (and occasionally .dat), where the number is the version number of the Z-machine on which the file is intended to be run, as given by the first byte of the story file.

- [Digital Antiquarian](https://www.filfre.net/) Z-Machine articles:

  - https://www.filfre.net/2019/10/new-tricks-for-an-old-z-machine-part-1-digging-the-trenches/
  - https://www.filfre.net/2019/11/new-tricks-for-an-old-z-machine-part-2-hacking-deeper-or-follies-of-graham-nelsons-youth/
  - https://www.filfre.net/2019/11/new-tricks-for-an-old-z-machine-part-3-a-renaissance-is-nigh/

## ZIL Overview

> ZIL is short for **Zork Implementation Language**, a programming language developed by Infocom and based on MDL, which itself is a version of Lisp.

- [IFWiki](https://www.ifwiki.org/index.php/ZIL)

- [What is ZIL anyway? // Zarf Updates](http://blog.zarfhome.com/2019/04/what-is-zil-anyway.html)

- [Infocom Source Code and Resources // Z-Machine Matter](https://www.z-machine-matter.com/2019/05/infocom-source-code.html)

- [ZIL and the Z-Machine // Digital Antiquarian](https://www.filfre.net/2012/01/zil-and-the-z-machine/)

- [ZIL - Zork Implementation Language - History of the Language // YouTube](https://www.youtube.com/watch?v=-oPIXEn7xcE)

### MDL Resources

> MDL (Model Development Language,or colloquially also referred to as More Datatypes than Lisp or MIT Design Language is a programming language, a descendant of the language Lisp. Its initial purpose was to provide high level language support for the Dynamic Modeling Group at Massachusetts Institute of Technology's (MIT) Project MAC. It was initially developed in 1971 on a PDP-10 computer on a time-sharing operating system named Incompatible Timesharing System (ITS).

> From: https://en.wikipedia.org/wiki/MDL_(programming_language)

- [_The MDL Programming Language_ by S. W. Galley and Greg Pfister // GitHub](https://github.com/taradinoc/mdl-docs)

  - [HTML Version](https://mdl-language.readthedocs.io/en/latest/)

  - [PDF Version](https://apps.dtic.mil/sti/pdfs/ADA070930.pdf)

- [_MDL Programming Language Primer_ by Michael Dornbrook and Marc Blank](http://publications.csail.mit.edu/lcs/pubs/pdf/MIT-LCS-TR-292.pdf)

- [_A Device-Independent Graphics Manager For MDL_ by Poh Chuan Lim](https://dspace.mit.edu/bitstream/handle/1721.1/102210/10219781-MIT.pdf#page=69)

- [_Graphics Programming and Monitoring_ by J.C.R. Licklider](https://apps.dtic.mil/dtic/tr/fulltext/u2/a197342.pdf)

- [Muddle](https://github.com/PDP-10/muddle/blob/d73ace3f3292e320b461b8fcd2e9f5dc5d9684d7/mim/development/mim/doc.mss)

### Lisp Resources

> The Lisp language is the oldest and most widely used functional language. Lisp is essentially typeless, but originally had two types of data objects: atoms and lists. Indeed, Lisp stands for “LISt Processing.” Lisp has long been a popular language for applications in artificial intelligence.

> From: https://www.sciencedirect.com/topics/computer-science/lisp

- https://en.wikipedia.org/wiki/Lisp_(programming_language)

- [Lisp Overview](https://www.tutorialspoint.com/lisp/lisp_overview.htm)

- [A Brief Introduction to Lisp](https://courses.cs.vt.edu/~cs1104/TowerOfBabel/LISP/Lisp.outline.html)

- [Lisp // Byte Magazine, 1979](https://archive.org/details/byte-magazine-1979-08)

## Tools

### ZILF

> ZILF is an open-source ZIL compiler, Z-machine assembler, world model, and related tools written by Jesse McGrew. ZILF has been said to stand for either Zork Implementation Language of the Future or The ZIL Implementation You Really, Really Like. It is written in C#, and runs under Windows, or under MacOS or Linux using Mono. It takes ZIL source code and compiles it into Z-machine assembly code, which is then passed to ZAPF to make the final Z-code story file.

- [ZILF Home](https://foss.heptapod.net/zilf/zilf/-/wikis/home)

  - [0.9 Release Notes](https://foss.heptapod.net/zilf/zilf/-/wikis/Releases/0.9/Release-Notes)

  - [ZILF Downloads for Linux, MacOS, and Windows](https://foss.heptapod.net/zilf/zilf/-/wikis/Releases/0.9/Downloads)

  - [Visual Studio Code Extension for ZIL](https://marketplace.visualstudio.com/items?itemName=zilf.zil-language)

#### ZIL Documentation

- [_Learning ZIL: Everything You Always Wanted to Know About Writing Interactive Fiction But Couldn't Find Anyone Still Working Here to Ask_, by Steven Eric Meretzky, Infocom, Inc.](https://archive.org/details/Learning_ZIL_Steven_Eric_Meretzky_1995)

- [_ZIL_ by Marc S. Blank ](https://github.com/heasm66/ZIL-Resources/blob/master/ZILCourse.pdf)

- [Internal Secrets of Infocom Games](https://ifsecrets.blogspot.com/2019/02/introduction.html)

  - [GitHub Repo (including PDF)](https://github.com/ZoBoRf/InternalSecretsOfInfocomGames)

- [ZILF Reference Guide // Github](https://github.com/heasm66/ZILF-Reference-Guide?fbclid=IwAR3iQdc8ju66RY0YWqH-tin7qigwXqvxwU4VuZQ6zGxBqPoAsFKhqKoHrqw)

  - [PDF Version](https://github.com/heasm66/ZILF-Reference-Guide/blob/master/ZILF%20Reference%20Guide.pdf)

    > The goal is to list all commands in the ZILF developing environment with a short description of the command and some short examples to illustrate how the command is used.

- [_ZIP: Z-language Interpreter Program_, by Joel M. Berez and Marc S. Blank](https://github.com/heasm66/ZIL-Resources/blob/master/spec-zip.pdf)

- [_EZIP: Z-language Interpreter Program (Expanded)_, by Joel M. Berez and Marc S. Blank](https://github.com/heasm66/ZIL-Resources/blob/master/spec-ezip.pdf)

- [_ZIP/EZIP/XZIP: Z-language Interpreter Program_, by Joel M. Berez, Marc S. Blank, and P. David Lebling](https://github.com/heasm66/ZIL-Resources/blob/master/spec-xzip.pdf)

- [_ZIP/EZIP/XZIP/YZIP: Z-language Interpreter Program_, by Joel M. Berez, Marc S. Blank, and P. David Lebling](https://github.com/heasm66/YZIP-Specifications/blob/master/yzip%20specifications.pdf)

#### ZIL Tutorials

- Adam Sommerfield's _Learning Zil and Zilf_ series // YouTube

  - [Behind the Scenes #001](https://www.youtube.com/watch?v=lGk-_-LG6-s)

    > A 65 min behind-the-scenes video on VERSION and STATUS-LINE.

  - [Episode 1 - Downloading and installing ZILF](https://www.youtube.com/watch?v=FBiWTVTpYDo&list=PLigB6rWYx7UxtT581XgrXLhzBK9fqyncC&index=1)

  - [Episode 2 - Visual Studio Code for ZIL](https://www.youtube.com/watch?v=P-G9qbbnOnw&list=PLigB6rWYx7UxtT581XgrXLhzBK9fqyncC&index=2)

  - [Episode 3 - Setting up Directory Structure](https://www.youtube.com/watch?v=05gG1Hae4VA&list=PLigB6rWYx7UxtT581XgrXLhzBK9fqyncC&index=3)

  - [Episode 4 - Adam's Extra Resources](https://www.youtube.com/watch?v=8hdVhtPNW8E&list=PLigB6rWYx7UxtT581XgrXLhzBK9fqyncC&index=4)

    > Extra Samples plus the [verbs_plus.zil file](https://drive.google.com/drive/folders/1xJ8FOxNC6tVLtSXWfzs_P-jFD4HNvaKz)

#### ZIL Source Code

- [Adam Sommerfield's _Cleaned-Up Source Collection_](https://drive.google.com/drive/folders/1BYQdh8gCsAo-kbdmf9MC0Dusskrs_gRN)

  > Large collection of Infocom source, test games, and ZIL libraries. If you want useful samples of ZIL in action -- check this out.

### Inform 6/7

> Since its invention (by Graham Nelson in 1993), Inform has been used to design some hundreds of works of interactive fiction, in eight languages, reviewed in periodicals ranging in specialisation from XYZZYnews to The New York Times. It accounts for around ten thousand postings per year to Internet newsgroups. Having started as a revival of the then-disused Infocom adventure game format, the Z-Machine, Inform came full circle when it produced Infocom's only text game of the 1990s: Zork: The Undiscovered Underground, by Mike Berlyn and Marc Blank.

- [https://en.wikipedia.org/wiki/Inform](https://en.wikipedia.org/wiki/Inform)

#### Inform 6

- [Inform 6 Home](https://www.inform-fiction.org/)

- ...more here

#### Inform 7

- [Inform 7 Home](http://inform7.com/)

  - [Inform 7 for Programmers // IFWiki](https://www.ifwiki.org/index.php/Inform_7_for_Programmers)

    - [Alternate HTML version](http://www.plover.net/~pscion/inform7.html)

    - [PDF Version](http://www.plover.net/~pscion/Inform%207%20for%20Programmers.pdf)

## Infocom

- [Zarf's _The Obsessively Complete Infocom Catalog_](https://eblong.com/infocom/?fbclid=IwAR3Zvyw8n4uPoAh9AmIjDjnUdtd4KLutjBChA7jttjF6K4oefWgvQMJX7pM)

  > If 'awesome-z-machine' could be summed up in a single link, this is it.

- [Infocom Resources // Archive.org](https://archive.org/search.php?query=creator%3A%22Infocom%22)

- [Infocom Gallery](http://gallery.guetech.org/)

- [Zork and the Future of Computerized Fantasy Simulations // Byte Magazine](https://web.archive.org/web/20120502071956/http://www.csd.uwo.ca/Infocom/Articles/byte.html)

- [The Roots of Infocom // Digital Antiquarian](https://www.filfre.net/2012/01/the-roots-of-infocom/)
- [History of Infocom](http://www.infocom-if.org/company/company.html)

- [Down From the Top of Its Game: The Story of Infocom (PDF)](http://web.mit.edu/6.933/www/Fall2000/infocom/infocom-paper.pdf)

- [Milliways: Infocom's Unreleased Sequel to Hitchhiker's Guide to the Galaxy](https://waxy.org/2008/04/milliways_infocoms_unreleased_sequel_to_hitchhikers_guide_to_the_galax/)

- [Infocom Cabinet](https://archive.org/details/infocomcabinet)

  > A collection of digitized scans from a large cache of documents related to the game publisher Infocom, Inc. of Cambridge, MA. Assembled by Steven Meretzky of Infocom.

- [Get Lamp: A Documentary about adventures in Text](http://www.getlamp.com/)

  - [The Get Lamp tapes // YouTube](https://www.youtube.com/playlist?list=PL095D66011B4D43DC)

  - [Get Lamp review // Z-machine-matter.com](https://www.z-machine-matter.com/2010/09/get-lamp-dvd.html)

  - [Infocom: The Documentary // YouTube](https://www.youtube.com/watch?v=OXNLWy7rwH4)

### Source Code

#### Historical Source

> A collection of Infocom source code files, for education and perusal.

- https://github.com/historicalsource
