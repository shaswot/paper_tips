# paper_tips
Tips for writing paper

Setting up the format of a paper for double-blind review is always a pain. The following answer from Stack Overflow is a lifesaver to save space from the copyright/referencing boxes in ACM papers.

https://tex.stackexchange.com/questions/346292/how-to-remove-conference-information-from-the-acm-2017-sigconf-template/346309

Add the following lines below the \documentclass line.

\settopmatter{printacmref=false} % Removes citation information below abstract
\renewcommand\footnotetextcopyrightpermission[1]{} % removes footnote with conference information in first column
\pagestyle{plain} % removes running headers
