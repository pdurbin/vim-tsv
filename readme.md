Inspired by this post. . .

Vim and plaintext data files: http://briancarper.net/blog/552/

. . . this plugin sets Vim's [listchars][] for files ending in .tsv (tab separated values) and turns off wrap, such that a file might look like this:

    Name»-------------Language»---------Current Release»--Last Updated»----…
    Jekyll»-----------Ruby»-------------0.11.2»-----------2011-12-27»------…
    Hyde»-------------Python»-----------0.4»--------------2009-10-06»------…
    ikiwiki»----------Perl»-------------3.20120629»-------2012-06-29»------…

If the columns are too wide (or too narrow) for the data you're viewing, you can change the tabstop with `set tabstop = 14`, for example.

[listchars]: http://vimdoc.sourceforge.net/htmldoc/options.html#%27listchars%27
