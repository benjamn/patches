# RATIONALE

Why on earth would I use git to manage a mercurial patch queue?  Not because git is more efficient than mercurial; any advantage would be unappreciable for so few files.  Nor because I am particularly more comfortable with git than mercurial; I am not.  No, the real reason I'm using git in preference to mercurial is that I want to host my patch queue remotely, publicly, and github is simply the best free hosting solution for revision-controlled code.

This decision has the side effect of making my day-to-day work at Mozilla completely transparent.  For some time now I've been wondering how best to take advantage of this incredible luxury, and I think I've found my way.

Watch my progress if you're interested, or if you just want to give my work ethic a boost.  Having an audience is tremendously encouraging.

## Some other benefits I've noticed:

- Not having the ".hg" directory in my patches directory means I can issue mercurial commands from inside the patches directory.

- Mercurial behaves nicely when no "status" file exists, so I've chosen not to commit that file.
