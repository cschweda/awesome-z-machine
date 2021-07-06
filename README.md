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

### Lisp Resources

> The Lisp language is the oldest and most widely used functional language. Lisp is essentially typeless, but originally had two types of data objects: atoms and lists. Indeed, Lisp stands for “LISt Processing.” Lisp has long been a popular language for applications in artificial intelligence.

> From: https://www.sciencedirect.com/topics/computer-science/lisp

- https://en.wikipedia.org/wiki/Lisp_(programming_language)

- [Lisp Overview](https://www.tutorialspoint.com/lisp/lisp_overview.htm)

- [A Brief Introduction to Lisp](https://courses.cs.vt.edu/~cs1104/TowerOfBabel/LISP/Lisp.outline.html)

- [Lisp // Byte Magazine, 1979] (https://archive.org/details/byte-magazine-1979-08)

## Tutorials

## Websites

## Tools

## Infocom

### History

- [The Roots of Infocom // Digital Antiquarian](https://www.filfre.net/2012/01/the-roots-of-infocom/)
- [History of Infocom](http://www.infocom-if.org/company/company.html)
- [Down From the Top of Its Game: The Story of Infocom (PDF)](http://web.mit.edu/6.933/www/Fall2000/infocom/infocom-paper.pdf)

#### Infocom Cabinet

> A collection of digitized scans from a large cache of documents related to the game publisher Infocom, Inc. of Cambridge, MA. Assembled by Steven Meretzky of Infocom.

- [Hitchhikers Guide to the Galaxy](https://archive.org/details/InfocomCabinetHitchhikersGuide)
- [Memos: 1983](https://archive.org/details/InfocomCabinetMemos1983)
- [A Mind Forever Voyaging](https://archive.org/details/InfocomCabinetAMindForeverVoyaging)
- ...more here

### Source Code

#### Historical Source

> A collection of historical source files, for education and perusal.

- https://github.com/historicalsource

  - [Deadline](https://github.com/historicalsource/deadline)
  - [Hitchiker's Guide to the Galaxy](https://github.com/historicalsource/hitchhikersguide)
  - [Planetfall](https://github.com/historicalsource/planetfall)
  - [Starcross](https://github.com/historicalsource/starcross)
  - [Suspended](https://github.com/historicalsource/suspended)
  - [Zork Mainframe](https://github.com/historicalsource/zork)
  - [Zork MDL](https://github.com/historicalsource/zork-mdl)
  - [Zork 1](https://github.com/historicalsource/zork1)
  - [Zork 2](https://github.com/historicalsource/zork2)
  - [Zork 3](https://github.com/historicalsource/zork3)
  - [Bureaucracy](https://github.com/historicalsource/bureaucracy)
  - [Trinity](https://github.com/historicalsource/trinity)
  - [Stationfall](https://github.com/historicalsource/stationfall)
  - ...more here
