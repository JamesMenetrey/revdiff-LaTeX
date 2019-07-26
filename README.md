# **revdiff**: a LaTeX revision and diff package

**revdiff** was created to build diff documents with which authors
can **ease the work of reviewers** by marking changes in the text, adding
tags and adding comments.


## Usage

* `\usepackage[mode]{revdiff}` mode can be set to `revision` or `clean`. `revision` mode displays revision details. `clean` mode hides revision details.
* `\rlegend` prints built-in legend text.
* `\rnew{this is new text}` for text additions.
* `\rold{this is old text}` for text deletions.
* `\rchange{This is an}{inline change}` is similar to `\rnew` and `\rold`, but in one command.
* `\rcomment{This is a comment}` to add comments.
* `\renclose{This is a comment}{here the text}` to add comments to a specific part of the text.
* `\rtag{a tag}` to add tags to the text.
* `\rtchange{tag}{This is an}{inline change}` is similar to `\rchange` but including a tag.
* `\rtcomment{tag}{This is a comment}` is similar to `\rcomment` but including a tag.
* `\rtenclose{tag}{This is a comment}{here the text}` is similar to `\renclose` but including a tag.

Check the result of using these commands [here >>](https://github.com/pedromateo/latex_revdiff/blob/master/test.pdf)

## Wanna help?

TODO list:

* tag index including links to tags. Index is created by using
  `\rtagindex` command. 




