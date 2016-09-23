# Lab 4

### File changed
https://www.freebsd.org/doc/en_US.ISO8859-1/books/porters-handbook/using-x11.html

### Diff
```
Index: special/chapter.xml
===================================================================
--- special/chapter.xml	(revision 49425)
+++ special/chapter.xml	(working copy)
@@ -1303,7 +1303,7 @@
       <title>Getting a Fake <envar>DISPLAY</envar> with Xvfb</title>
 
       <para>Some applications require a working X11 display for
-	compilation to succeed.  This pose a problem for machines
+	compilation to succeed.  This poses a problem for machines
 	that operate headless.  When this variable is used,
 	the build infrastructure will start the virtual framebuffer
 	X server.  The working <envar>DISPLAY</envar> is then passed
```

### Bug Report
[https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=212941](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=212941)

### Reflection
In this lab, I submitted a report on typo error in one of the FreeBSD's handbooks. Going through the huge documentation in this lab, I have learned that virtually all the common problems and how-tos in using FreeBSD are documented, which allow new and old users of the OS to get answer any time they get stuck by just searching through the documentation. If I have to work on any opensource project, having good documentation in place would definitely help getting me on board and start getting into doing work for that project.
