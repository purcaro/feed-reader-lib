feed-reader-lib
===============

Fast, thread-safe, extensible &amp; platform independent feed reader library in C++, supports RSS, ATOM, RDF

===============
FeedReader is a C++ library designed to retrieve and parse web feeds such as RSS, ATOM and RDF.
Features:

FeedReader was designed to scale: it is fast, thread-safe, extensible and platform-independent.

In FeedReader, all feeds are transformed via XSL to a uniform schema before being parsed.
This means that in order to extend FeedReader to support a new feed format, all that is needed is a new XSL file.
The library comes with XSL files supporting for the following feed formats:

    * RSS 1.0
    * RSS 2.0
    * ATOM 0.3
    * ATOM 1.0
    * RDF

An iterator interface is provided to the feed elements parsed.

Using the library is simple and sample client code is located in the examples directory.
Dependencies:

The FeedReader library is dependent on, and was tested with the following libraries/versions:

    * Boost 1.36 (was also tested with 1.33_1)
    * libcurl 7.18.1
    * Xerces 2.8.0
    * Xalan 1.10.1
    * Zlib 1.23 (required by CURL)

===============
FeedReader was created by Yoav Aviram (yoav.aviram AT gmail DOT com)

===============
converted from https://code.google.com/p/feed-reader-lib/ by
git svn clone --stdlayout --no-metadata -A authors  http://feed-reader-lib.googlecode.com/svn/
git remote add origin git@github.com:purcaro/feed-reader-lib.git
git config branch.master.remote origin
git config branch.master.merge refs/heads/master

Authors:
(no author) = no_author <no_author@no_author>
yoav.aviram = Yoav Aviram <yoav.aviram@gmail.com>
