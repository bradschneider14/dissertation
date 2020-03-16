# Wright State University LaTeX thesis/dissertation style file
This repository contains a set of files for LaTeX users writing thesis or dissertations at *Wright State University*. There are a number of other WSUs.

The LaTeX file itself should be self-documenting, so the user is left
to their own to edit it and modify it with the contents of their
thesis/dissertation. There is a bit of demoing of LaTeX that happens
in the document, but no claims are made that it is sufficient to teach
LaTeX. A rather [dry video of me walking through the template](https://youtu.be/6XnMzmFH_u0) can be found on youtube. Recent updates should preclude the need to touch the style
file. Please feed your corrections to me!

Use this and you will have a consistent document that meets Wright State University
guidelines. Don’t add your own formatting. Use only *structure* commands. For instance, ``\emph`` instead of ``\textit``.

If you find bugs, the best thing to to is fork the repository, correct the issue, then submit a pull request so that the template and other files may be improved. Incorporating your corrections is the best way to thank me and others who have worked on this so far.

Every effort has been made to meet the Wright State University School of Graduate Studies Guidelines,
and this template may actually be good enough, however no warrantee is
expressed or implied. Things change, and the template will likely have to be continuously updated.


## Theses/Dissertations using LaTeX


LaTeX is hands down the best tool to use when writing your thesis or
dissertation. Instead of arguing the point, let me make a simple
statement. Users of LaTeX know how to use MS Word, but use LaTeX
instead. Users or MS Word don’t know how to use LaTeX. It’s that simple.
If your adviser won’t let you use LaTeX, my condolences. Your document
will lack the polish of a professional typesetting system (Do you think
journals typeset using MS Word?), and you will be tortured by cross
reference and citation issues and inconsistencies. You likely use Word
because that’s all you’ve ever known. Hopefully you’ll stopped crawling
(using MS Word) and now walk upright (use LaTeX). If you don’t, c’est la
vie. Your loss. If you want to know a little about why to use LaTeX,
consult some of the references below.

Regardless of whether you use LaTeX, it’s important that you know how to
properly archive your data. If you don’t store your data in a readable
format, you might as well delete it after you defend. You’ve made it
useless. If you want to save is for potential future use, read my
document on [archiving your data][]. It’s not a great document, but it’s
the best I’ve got.

## Plotting (even if you’re not using LaTeX)


Making quality looking plots can be a challenge. Most graphics don’t
have fonts and/or font sizes that match the text, or they are all fuzzy,
etc. One of the best package for generating publication quality graphs
is (still) [gnuplot][]. It allows you to specify the size of the resulting graphic
(so you don’t have to “squeeze it”) in your final document, the font,
the font size, tic marks, etc. You can plot functions, as well as data,
plus curve fit to it while plotting. It can be a little bit challenging
at first, so a good place to start is with a tutorial such at
[the one at Harvey Mudd College][] and [the one at Duke][]. Yes, you may think you
can do this as well in Excel, but the reality is the cartoony plots in
Excel look good in brochures and business presentations, not
engineering, math and science technical papers. There are many other options out there. Look to see what is being used by serious programmers, but you also have to weigh that against the value of your time. I've personally gravitated toward [matplotlib][] in [Python][].


Back to LaTeX:

-   Do not include file extensions when including files. LaTeX can
    choose the best you have, or switch from eps to pdf etc.
-   Use vector graphics at every instance possible (anything that is not
    a photograph). At the very least, save a version in vector form for
    your adviser. See [archiving your data][].



## Some Basic Introductions to LaTeX


These are, or will be, out of date, but are a good start in learning
LaTeX. Pick and choose as you need. Get the more updated documents from
[CTAN][] (look for the dtx or tex file in the appropriate package) to get
the latest documents. Send me the new file and I’ll post it.

-   [LaTeX-Tutorial][]
-   [AMS LaTeX (How to do Math, AMS User Guide)][]
-   [Gentle Introduction to TeX][]
-   [Graphics Package][]
-   [Making Double Lines in Tables][]
-   [A Short Intro to LaTeX][]
-   [For Mac Users][]
-   [Windows users links][]

## Platform specific advice
### Windows Users


My current recommendations are to use:

1.  [JabRef][] (Editing Bibliography database)
2.  Either [MikTeX][] or [TeXLive][] (I don’t have enough knowledge to make
    a recommendation)
3.  [texstudio][]
4.  [Ghostscript][] (you may want to use it to convert ps files to
    eps or pdf files)
5.  Adobe Acrobat Reader or another PDF viewer.

Go to [TeX on Windows][] for links.

### Mac Users
Look at the [TeX on Mac Wiki][] and at [MacTeX][].

### Cloud-based tools

There are 3 cloud-based LaTeX editors that I am familiar with.
-   [ShareLaTeX][]
-   [Overleaf][]
-   [Cloud LaTeX][]

[ShareLaTeX][] and [Overleaf][] have merged. For all practical purposes, I think [Overleaf][] is the way to go. Eventually they will be identical. [Cloud LaTeX][] is newer and I have even less experience with it.

I have highly respected colleagues that swear by [Overleaf][]. I don't have a lot of experience with it yet, but it's certainly on my radar. In fact, the WSU Thesis Template is already on [Overleaf][] ready to go.

[Overleaf][] provides *typeset as you go* which is very cool.

Because the files are in the cloud, some operations are different from using a local application. See [How to include a bibliography using bibtex][]. Frankly, the easiest way is to maintain your database on [Zotero][].

## Graphical User Interface (GUI) Version (Multi-platform)

[LyX][] is something like a GUI version that is easier for a novice to work on, but can be somewhat limiting for someone comfortable with more power available only when editing the raw LaTeX. Dr. Klingbeil is a strong fan of it, but I find directly typing formulas and macros using a dedicated LaTeX editor (Emacs is my favorite) to be much faster. If LaTeX is intimidating to you, use LyX. It still provides most of the benefits over Word (better cross referencing, cleaner/professional looking output). However, I’m not familiar with using my style file with it (or if it’s even possible). However, Jeremy Daily did his dissertation in LyX just fine.

## Checking Spelling

There is no excuse for not checking spelling in your latex document. Note that you cannot blindly believe whatever the spell checker says. Words such as “there” and “their” can be spelled correctly but be the wrong choice.

1.  Mac users: Use [CocoAspell][]
2.  Windows users: Use [aspell for Windows][]
3.  Linux users: install aspell and use it. It should be available as a
    package for your distribution.

## Checking Grammar

[LanguageTool][] can be used on any platform with Java 5.0 or later installed. Be aware that it provides suggestions. Just like spelling, it is helpful in finding potential errors, not actual errors, and will often provide bad suggestions, just like MSWord. You have to be a competent judge, or you have to find one.

## Making Presentations (in LaTeX)

Here are [a number of ways to make presentations][] out of your thesis
easily. All the useful parts of PowerPoint without the garbage. In most
cases you make PDF files from your latex document. Buttons, and
incremental displays, and… can be set up.

The package includes a presentation template which you may choose to use.

Like this module, `buy me a coffee! <https://www.buymeacoffee.com/s6BCSuEiU>`_

  [TeX on Windows]: http://mactex-wiki.tug.org/wiki/index.php?title=TeX_on_Windows
  [LyX]: http://www.lyx.org
  [CocoAspell]: http://ict.usc.edu/~leuski/cocoaspell/
  [aspell for Windows]: http://aspell.net/win32/
  [LanguageTool]: https://languagetool.org/
  [a number of ways to make presentations]: http://www.miwie.org/presentations/presentations.html
  [WSU School of Graduate Studies Guidelines]: http://www.wright.edu/sogs/thesis/format.html
  [CTAN]: http://www.ctan.org/
  [AMS LaTeX (How to do Math, AMS User Guide)]: amsldoc.pdf
  [Gentle Introduction to TeX]: gentle.pdf
  [Graphics Package]: grfguide.pdf
  [Making Double Lines in Tables]: hhline.pdf
  [A Short Intro to LaTeX]: lshort.pdf
  [For Mac Users]: http://mactex-wiki.tug.org/wiki/index.php/Main_Page
  [Windows users links]: http://mactex-wiki.tug.org/wiki/index.php?title=TeX_on_Windows
  [archiving your data]: http://josephcslater.github.io/archiving-and-plotting-data.html
  [gnuplot]: http://www.gnuplot.info/
  [the one at Harvey Mudd College]: http://www.cs.hmc.edu/~vrable/gnuplot/using-gnuplot.html
  [Cloud LaTeX]: https://cloudlatex.io
  [Overleaf]: https://www.overleaf.com
  [ShareLaTeX]: https://www.sharelatex.com/
  [the one at Duke]: http://www.duke.edu/~hpgavin/gnuplot.html
  [python]: http://www.python.org
  [matplotlib]: http://matplotlib.org
  [TeX on Mac Wiki]: http://mactex-wiki.tug.org
  [MacTeX]: https://tug.org/mactex/
  [LaTeX-Tutorial]: https://www.latex-tutorial.com
  [JabRef]: http://www.jabref.org
  [MikTeX]: www.miktex.org
  [TeXLive]: https://www.tug.org/texlive/
  [texstudio]: www.texstudio.org
  [Ghostscript]: https://www.ghostscript.com/download/gsdnld.html
  [How to include a bibliography using bibtex]: https://www.overleaf.com/help/97-how-to-include-a-bibliography-using-bibtex#.WfuMP9vMw4M
  [Zotero]: www.zotero.org
