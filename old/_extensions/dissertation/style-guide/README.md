For instructions on using LaTeX to prepare UTD dissertations, please read the sample.pdf document that accompanies this file.

This file archive should contain the following four files:

(1) "readme.txt" - this file

(2) "utdthesis.cls" - the main document class file for UTD dissertations.  Put this file in the same folder as your main .tex file.

(3) "sample.tex" - a sample main .tex file that you should compile with pdflatex in order to test whether your LaTeX installation is working and compatible.  You can use the sample as a starting point to create your dissertation.

(4) "sample.pdf" - the expected result of compiling sample.tex on a working LaTeX installation using pdflatex.  The contents of the document provide instructions on using the template to write UTD dissertations.


Debugging tips:

Always compile sample.tex unchanged first and look at the results.  If it doesn't compile or something looks wrong, then it probably means something is wrong with your LaTeX installation.  Try reinstalling LaTeX or using a different (e.g., newer) LaTeX version.  Always use "pdflatex" to compile your documents.  (Do not generate a dvi file and then convert it to pdf.  That compilation method is outdated and can introduce errors.)

If something stops working after you start replacing the sample with your dissertation text, it usually means you've loaded a package that is overriding the template formatting, or you've accidentally redefined a LaTeX macro or length that is needed by the template.  To debug such situations, reduce the text of your document to the bare minimum required to exhibit the problem, then slowly start removing packages and definitions until the problem disappears.  This will isolate the source of the incompatibility.

When checking document measurements (e.g., margin sizes, line spacing, etc.), do not measure a printed copy.  Some printers and software resize things during physical printing, so measuring a printed version is not reliable.  Likewise, do not rely on viewing the document in a web browser.  Some web browsers inaccurately render pdfs.  The most reliable way to measure distances in a pdf is to view the document using Adobe software (e.g., Acrobat) and use its digital ruler.


Disclaimers:

These instructions (including the sample.pdf) are not an attempt to teach LaTeX.  Please consult an online guide for that.  (The sample.pdf makes a recommendation.)

Using this template does not guarantee that your dissertation satisfies UTD's formatting requirements.  It is merely an aid.  You must still read and satisfy the formatting requirements as documented by the graduate office.
