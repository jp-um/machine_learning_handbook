# NOTE OF IMPORTANCE

**Your work is not considered as submitted until your entry appears in the handbook `.pdf` file in my repository (master branch).**

# A Machine Learning Handbook

A student-sourced Machine Learning Handbook for ICS5110.  Instructions for submission:

1. Clone the repository
2. Edit the `ics5110_ml_handbook.tex` file
   * Find the `TODO` labels inside this file (3 instances), change/add your stuff accordingly
3. Add your term file and bibliography to the `terms` directory.  This should have 
the form of `term_initials.tex` where `term` is your actual term and 
`initials` are your initials (e.g. `overfitting_jpe.tex`).  Also add your
bibliography (i.e. `term_initials.bib`) there.
4. Create a pull request ([read here](https://help.github.com/articles/creating-a-pull-request/) for more details)

Submit as early as possible as you are bound to get feedback on your work (no need to wait for the deadline, everyone is doing something different anyway).  Don't expect to get feedback if you submit your work close to the deadline

If you do not see your entry on the master branch, then you have not successfully submitted your entry to the handbook.

## Guidelines

After a number of you made the following mistakes I think it makes sense to group everything here:

1.  Your submission must compile on Linux (using `pdflatex`).  No errors should be reported.  *No, I will not fix your submission for you.*
1.  Your submission should look good (e.g. no overlapping text or images, etc.) when compiled with LaTeX
1.  Your submission should work with the LATEST master version.
1.  Do not commit platform-specific files (e.g. `.DS_Store`)
1.  All tex/bib files should go under `terms` directory
1.  All graphics files should go under your topic subdirectory under `graphics`
1.  Use proper sectioning/subsectioning
1.  `.bib` references do not need `DOI`, `pdf`, `keywords` or `abstract` entries (other attributes to delete are `Remove Date-Added`, `Date-Modified`, `Bdsk-File-1`)
1.  No abbreviations (e.g. they're), but also no Fig., Eq. etc.  This is a formal scientific document, not an email.
1.  Use non breaking space between a Figure and its number, e.g. `Figure~\ref{fig:jp}`
1.  Make sure to index important keywords in your entry (look [here](https://en.wikibooks.org/wiki/LaTeX/Indexing) for details how to do this).  Multi-page index entries should have paired start and end delimiters.
1.  When you submit a Pull Request make sure it is against the latest master version
1.  Your entries should be in alphabetic order (e.g. cross-validation comes before ROC)
1.  Use proper and detailed figure, table and equation captioning
1.  Do not hardcode spaces in the template
1.  Understand the difference between `\citet` (reference in text) and `\citep` (reference in brackets)
1.  Make sure your references are not duplicated (keep in mind someone who committed their entry before may be using the same book/paper).  Please double check
1.  Do not hardcode author names -- always use `\citep` or `\citet` commands
1.  If you have an equation, the paragraph immediately after should explain all the symbols used (this is not optional)
1.  Avoid sentences which have zero information content, e.g. _Structural Risk Minimization (SRM) is a technique first developed by Vapnik and Chervonenkis in their book from 1974_.  (Note this tells you nothing about the method).
1.  Index entries must be meaningful (e.g. _overview_ is not a good index entry, overview of what??)
1.  Bibliographic entries should be scholarly in nature (not someone's blog or lecture notes -- find the original paper!)
1.  If you have an online resource in your bibliography you need the url (but not for papers)
1.  Index entries should be human (not machine!) readable
1.  The punctuation for the sentence goes AFTER the parenthesis of a citation
1.  Do not use double quotes character `"` or fancy single quotes character.  In LaTeX to get double quotes use ` ``this''`.  For single quotes use `'` character **only**
1.  You should not have two (or more) headings immediately following each other.  You require some _preamble_; a sentence or two which explains what is coming next
1.  LaTeX adds spacing after periods, but you don't want this for common abbreviations such as (e.g. `e.g. some words`, i.e., et al.).  To tell LaTeX this is not the end of a sentence, mark the space with a backslash (e.g. `e.g.\ this entry`). 
1.  There should be **zero** BibTeX warnings
1.  URLs should go in footnotes (`\footnote{...}`)
1.  You should use linebreak (`\\`, `\newline`), page breaks and `\noindent` sparingly.  The template should take care of the typesetting for you
1.  Figure, Equation and Table should be capitalized when referred to as proper nound (e.g. as shown in Figure 2).
1.  When you take a figure from another paper you need to reference it in the caption; e.g. Reproduced from Ebejer et al. (2017).  If you have taken the idea from somewhere but reimplemented the graphic use _Adapted_ instead of _Reproduced_
1.  No hanging statements at bottom of page (e.g. _The operations which take place are the following:_ with a list at the top of the next page).  Use pagebreak hints to avoid this `\pagebreak[1]`.
1.  No text operators (e.g. `\textbf{...}`) inside maths environments (e.g. equation or `$...$`).
