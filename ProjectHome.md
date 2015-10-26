# Page Cache Management for Linux #

## Description ##

This tool allows the user to limit the amount of pagecache used by applications under Linux. This is similar to `nice`, `ionice` etc. in that it usually doesn't make an application go faster, but does reduce the impact of the application on other applications performance. This is especially useful for applications that walk sequentially through data sets larger than memory, as discarding their pagecache does not reduce their performance (although this tool does add overhead of about 2%).

Although related to [pagecache-tools](http://code.google.com/p/pagecache-tools/), pagecache-management seems to serve a rather different purpose and is solely in userspace.

## Getting the source ##
pagecache-management is still experimental. If you really want to check it out, it is probably best just to get the latest source:
> svn checkout http://pagecache-mangagement.googlecode.com/svn/trunk/ pagecache-mangagement-read-only
You can also [browse](http://code.google.com/p/pagecache-mangagement/source/browse) the source in trunk.


## News ##
See the [svn log](http://code.google.com/p/pagecache-mangagement/source/list). :)
