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
