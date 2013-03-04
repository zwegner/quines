Quines
======

Some old quines I wrote intermittently between 2008 and 2010, in C. Some of them are actually quine generators, in that their output doesn't match the original program, but is still a quine.

These were all done in pursuit of replicating a feat I had originally accomplished around 2003 or so (at age 15 or 16?): the mutually recursive double quine. That's a term I just made up, but the gist of it is basically program A generates program B, which in turn generates program A. I did this in 2 (perhaps 3) simple lines, one of them being a preprocessor line. Since I was able to do this at such a young age, it disappoints me that I wasn't able to do it again in my 20's. I had set up a quick vim macro to replace the contents of a window with the output of its compiled version, and had many basic quine-like templates to work from, but it didn't happen. The dates from these files indicate I came up with working quines in three spurts, many months apart. I've considered writing a python script to search for such a double-quine, but I know it would be rather complicated (and slow!), and I'd rather find a solution myself, as I did all those years ago. Perhaps it's time for another spurt...

Here are the dates from the files, since git doesn't track this info, if you happen to care about this for some mysterious reason:

    -rw-r--r-- 1 zach users  85 Aug  4  2008 quine1.c
    -rw-r--r-- 1 zach users 103 Aug  3  2008 quine2.c
    -rw-r--r-- 1 zach users 105 Aug  4  2008 quine3.c
    -rw-r--r-- 1 zach users 117 Aug  4  2008 quine4.c
    -rw-r--r-- 1 zach users  97 Aug  7  2008 quine5.c
    -rw-r--r-- 1 zach users  86 Dec 23  2009 quine6.c
    -rw-r--r-- 1 zach users 101 Dec 23  2009 quine7.c
    -rw-r--r-- 1 zach users 102 Apr  5  2010 quine8.c
    -rw-r--r-- 1 zach users  95 Apr  6  2010 quine9.c
