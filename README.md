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

**Submit as early as possible as you are bound to get feedback on your work (no need to wait for the deadline, everyone is doing something different anyway).  Don't expect to get feedback if you submit your work close to the deadline**

## Guidelines

After a number of you made the following mistakes I think it makes sense to group everything here:

*  Your submission must compile on Linux (using `pdflatex`).  No errors should be reported.  *No, I will not fix your submission for you.*
*  All tex/bib files should go under `terms` directory
*  All graphics files should go under your topic subdirectory under `graphics`
*  Use proper sectioning/subsectioning
*  Each `.bib` references do not need DOI, keywords or abstract entries
*  No abbreviations (e.g. they're)
*  Make sure to index important keywords in your entry (look [here](https://en.wikibooks.org/wiki/LaTeX/Indexing) for details how to do this)
*  When you submit a Pull Request make sure it is against the latest master version
*  Your entries should be in alphabetic order (e.g. cross-validation comes before ROC)
*  Use proper and detailed figure, table and equation captioning
*  Do not hardcode spaces in the template
*  Understand the difference between `\citet` (reference in text) and `\citep` (reference in brackets)
*  Make sure your references are not duplicated (keep in mind someone who committed their entry before may be using the same book/paper).  Please double check
