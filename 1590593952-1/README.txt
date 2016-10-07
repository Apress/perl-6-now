
This archive contains all of the listings from the book _Perl 6 Now: The Core 
Ideas Illustrated With Perl 5_ by Scott Walters (Apress, 2004, ISBN 1590593952).

This document contains some notes on the code examples that will ward off
some basic (but looming) confusion. If you've read the book carefully,
you've already had these pointed out to you (except for points 6 and 7). 

ABOUT THE LISTINGS
----- --- --------

1. Listings Start With Comments
   -------- ----- ---- -------- 
   Significant examples (large or small) start with a comment summerizing
   what the example is meant to illustrate. In most chapters, this comment 
   includes the version of Perl it was written for (some chapters default to
   Perl 5). If it is mixed and matched syntax, you'll see both "Perl 5" and 
   "Perl 6" in the comments.

2. Listings Have Redundant Code Removed
   -------- ---- --------- ---- -------
   Per Chapter 3, "Stricture by Default", all examples assume that the strict 
   and warnings modules are in effect. The "use strict" and "use warnings" lines 
   aren't repeated for each example. Likewise, the she-bang line, usually 
   #!/usr/bin/perl, has been left off of the listings.

3. Perl 6 Examples Are Tentitive
   ---- - -------- --- ---------
   Most of the examples are for Perl 5 and the examples for Perl 6 (or have 
   Perl 5 and Perl 6 syntax mixed to compare the languages) are _unrunnable_. 
   Please don't report to me that the Perl 6 examples are broken or that 
   examples mixing Perl 5 and Perl 6 don't compile. 

4. Most, But Not All, Listings Are Code
   ----- --- --- ---- -------- --- ----
   Not every listing is actually a code listing. There are 678 preformtted text
   blocks in _Perl 6 Now_, averaging more than one per page. This is too many to
   manually sift through, so I've automatically extracted them all. Some 
   listings are output examples and others are perhaps other things. The vast 
   majority of them are code examples. Collectively, these listings summerize
   the syntax and concepts behind the book, and I imagine they'll be useful
   as an on-line reference after you've read the book.

5. Listings Are Numbered Differently in This Archive
   -------- --- -------- ----------- -- ---- -------
   The "Listings" here don't have the same numbers as the "Listings" in the
   book. The next part of this document translates the book's listing
   numbers to the file names in this archive. See the next part of this document
   for a cross reference between the file names in this archive and the listing
   numbers in the book.

6. Report Broken Modules
   ------ ------ -------
   Some of the modules the code examples use may not work - when this happens,
   please let me know. While I was working on the book, and after it went to 
   press, a lot of dependency modules as well as the Perl core went through a 
   lot change with the result of many of these modules breaking. I'm working
   to correct this problem.

7. Code Listings Copyright Relinquished
   ---- -------- --------- ------------
   The Perl language source code contained in the book (and the source code 
   contained in this archive, which is nearly identical) is hereby placed into
   the public domain. You may use it without restriction. However, as the 
   book states: ``The information ... is distributed on an "as is" basis, 
   without warranty. Although every precaution has been taken in the 
   prepraration of this work, neither the author(s) nor Apress shall have any
   liability to any person or entity with respect to any loss or damage
   caused or alleged to be caused directly or indirectly by the information
   contained in this work.'' In other words, there is nothing intentionally
   malicious in the code, but there may be bugs, and the code may even
   completely fail to do what it was written to do. 

8. How to Report Problems
   --- -- ------ --------
   If you report an error, _including_ instructions needed to replicate it, 
   I'll do my best to make sure a correction is in the next edition and posted
   on the 'net as errata. Please check the online errata before filing a
   report. Keep in mind - when something "doesn't work" for you, it may be
   because of a version incompatability, your platform, an error in the code, 
   or, quite often, you made the mistake, not I. This is nothing to be ashamed
   of - it's really, really easy to make a mistake and often quite hard to see
   them. Please understand that I do sincerely hope that you get all of your 
   programs working, but due to the circumstances, I'm unable to provide 
   support for the code in the book or the modules documented in it (this is an 
   extension of the lack of warranty on the code and text). Remember that if 
   you can't figure out _why_ something doesn't work, it probably isn't an 
   error in the book. A good problem report contains at least a basic _why_. 
   The following kinds of error reports are examples of helpful reports: 
   a module doesn't pass its tests; there's a syntax error; the code triggers a
   warning or fatal error; the code contains a typo; I made a logic error and 
   you've found it; and so on. If you don't know _why_ something fails, 
   contact your local Perl Mongers group listed at http://pm.org. They're better
   equiped to help you. If you don't have a Perl Mongers group, search the 
   archives at Perl Monks at http://perlmonks.org (and, failing that, post to 
   Perl Monks). If you contact me and I don't reply, then you need to contact
   Perl Mongers instead. Also, there's a forum on the website - another reader
   might be able to explain ideas and code better than I can.

9. Web Site
   --- ----
   http://www.perl6now.com supports this book. That's the author's website. 
   Errata is being compiled there and submitted to Apress in batches. There's
   a chat area and a few other amusements and oddities along with a FAQ.
   Apress also has a website with a page for _Perl 6 Now_ which contains the
   official errata and code listings. Apress' website is at 
   http://www.apress.com.


LISTING NUMBERS
------- -------

Listings were primarily used for the few, rare large examples and for examples 
refered to from elsewhere in the book or chapter. These aren't necessarily the
most _interesting_ examples.

Listing in the Book          Listing in this Archive
----------------------------------------------------

                8-1          Chapter08/Listing014.txt
                8-2          Chapter08/Listing089.txt
                8-3          Chapter08/Listing094.txt
                8-4          Chapter08/Listing101.txt

                9-1          Chapter09/Listing003.txt
                9-2          Chapter09/Listing004.txt
                9-3          Chapter09/Listing009.txt
                9-4          Chapter09/Listing010.txt

               11-1          Chapter11/Listing004.txt
               11-2          Chapter11/Listing043.txt

               14-1          Chapter14/Listing004.txt
               14-2          Chapter14/Listing005.txt
               14-3          Chapter14/Listing030.txt
               14-4          Chapter14/Listing032.txt
               14-5          Chapter14/Listing067.txt
               14-6          Chapter14/Listing069.txt
               14-7          Chapter14/Listing070.txt

               16-1          Chapter16/Listing002.txt
               16-2          Chapter16/Listing003.txt
               16-3          Chapter16/Listing004.txt
               16-4          Chapter16/Listing005.txt
               16-5          Chapter16/Listing021.txt

               17-1          Chapter17/Listing009.txt
               17-2          Chapter17/Listing010.txt
               17-3          Chapter17/Listing011.txt
               17-4          Chapter17/Listing012.txt
               17-5          Chapter17/Listing014.txt
               17-6          Chapter17/Listing015.txt
               17-7          Chapter17/Listing019.txt
               17-8          Chapter17/Listing020.txt
               17-9          Chapter17/Listing021.txt

               19-1          Chapter19/Listing006.txt
               19-2          Chapter19/Listing007.txt

               20-1          Chapter20/Listing001.txt
               20-2          Chapter20/Listing002.txt
               20-3          Chapter20/Listing007.txt
               20-4          Chapter20/Listing008.txt
               20-5          Chapter20/Listing010.txt
               20-6          Chapter20/Listing011.txt
               20-7          Chapter20/Listing012.txt

               21-1          Chapter21/Listing011.txt
               22-2          Chapter21/Listing012.txt
               23-3          Chapter21/Listing014.txt

Finally, for no particular reason, here are the largest listings in the book and
their respective sizes in bytes:

Chapter21/Listing014.txt 1875
Chapter21/Listing012.txt 1534
Chapter17/Listing011.txt 1399
Chapter14/Listing004.txt 1286
Chapter08/Listing014.txt 1263
Chapter17/Listing009.txt 1163
Chapter11/Listing043.txt 1143
Chapter14/Listing070.txt 1100
Chapter08/Listing089.txt 991
Chapter14/Listing069.txt 934
Chapter08/Listing021.txt 898
Chapter14/Listing067.txt 874
Chapter07/Listing024.txt 853
Chapter16/Listing005.txt 837
Chapter07/Listing025.txt 834
Chapter09/Listing009.txt 803
Chapter14/Listing075.txt 780
Chapter07/Listing026.txt 778
Chapter09/Listing020.txt 774
Chapter14/Listing005.txt 713
Chapter08/Listing015.txt 707
Chapter09/Listing003.txt 692
Chapter10/Listing004.txt 676
Chapter08/Listing094.txt 662
Chapter17/Listing015.txt 640
Chapter14/Listing063.txt 637
Chapter20/Listing002.txt 629
Chapter05/Listing041.txt 628
