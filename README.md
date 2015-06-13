# About

This is a collection of scripts to hopefully make my life easier...  Hopefully...

# Installation

1. Install [homebrew](http://brew.sh)
2. Install pandoc `brew install pandoc`
3. Clone project and add into your path
4. Live happy

# Scripts

## docx (requires pandoc)

Generates a docx from the current directory.  Only grabs markdown/text files
that start with a number.  The idea is everyone uses word or a word compatible
editor.  You docx your current writing project, send them an e-mail, they add
comments and feedback, e-mail you back.  You make revisions.  Technology is once
again acknowledged as amazing.

Example directory:

* 01-Intro.md
* 02-Body.md
* 03-Conclusions.md
* README.md

Run: `docx draft`

Produces: draft.docx

Containing: 01-Intro.md, 02-Body.md, and 03-Conclusions.md

If you omit the file name, the file name is a hash of the contents.

## epub

Generates an epub from the current directory.  Only grabs markdown/text files
that start with a number.  The idea is you want to proof read a draft on your 
iPad or some e-reader.  You epub your current writing project, air drop it to
your iPad, read it.  You make revisions.  Technology is once again acknowledged
as amazing.

Example directory:

* 01-KillerOpening.md
* 02-Conflict.md
* 03-Resolution.md
* Outline.md

Run: `epub draft`

Produces: draft.epub

Containing: 01-KillerOpening.md, 02-Conflict.md, and 03-Resolution.md

If you omit the file name, the file name is a hash of the contents.
