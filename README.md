# A LyX template for UBC theses

## About this template

### What is this?
This is a template for Doctoral and Masters theses at the University of British Columbia. This template is for use with [LyX](https://www.lyx.org/), an open-source document preprocessor which is built upon LaTeX. I wrote my Masters thesis in LaTeX and found it to be a painful endeavour. I wrote my PhD thesis in LyX and it was significantly smoother.

### Who should use this?
Anyone who knows a bit of LaTeX but wants to try something a little easier (at least, I found it easier).

### Do I need to know anything about LaTeX and LyX to use this?
You should probably know a bit of LaTeX. There will be times when you need to insert LaTeX code (or ERT - Evil Red Text as LyX calls it) into your document. Also, because LyX renders with LaTeX, there will be some inevitable debugging. As for learning about LyX, you should have a bit of experience. You can get that through playing around with it and reading some tutorials (see step 2 below).

### Is this guaranteed to produce a properly formatted thesis?
No, it's not, but it did work for me and I've tried to ensure it will work for you. You should definitely review the UBC thesis [formatting requirements](https://www.grad.ubc.ca/current-students/dissertation-thesis-preparation/formatting-requirements). Also, submit your thesis for [pre-review](https://www.grad.ubc.ca/current-students/dissertation-thesis-preparation/pre-reviews) well ahead of any deadlines to catch any formatting issues.

Also, there's probably a better way to accomplish many of the formatting intricacies than I've done in the template. That's just what worked for me.

### I want to report a bug
Leave a comment here on Github, I'll try to get to it.

### Where is your thesis?
You can find my PhD thesis, *T1 relaxation and inhomogeneous magnetization transfer in brain : physics and applications*, [here](https://dx.doi.org/10.14288/1.0375841)

## Usage
### Step 1: Set up a bibliography file
I've included an example refs.bib file. You should make your own with a reference manager. I used [JabRef](http://www.jabref.org/) which was great (and free).

### Step 2: Learn a bit about LyX
You can probably figure this out as you go with a bit of Googling. However, I recommend taking a look at *Essentials of LyX* tutorial (under the tutorial list on [this page](https://wiki.lyx.org/LyX/Tutorials)). Also, this template makes heavy use of multidoc, so have a look through that [FAQ](https://wiki.lyx.org/FAQ/Multidoc). It explains the differences between includes, inputs, and why there is a preamble.tex file.

### Step 3: Download the template
Click on **Clone or Download** above then **Download zip**

### Step 4: Change the document titles
Open thesis.lyx. On the *Document* menu go to *Settings* then click *PDF Properties*. Fill out the Header information.

### Step 5: Try to render it
Go *Document* -> *view (pdflatex)*. If all goes well, you'll see a pdf of the template come up. If not, you'll have to debug some latex errors... That will 95% be because of some missing packages. Make sure they're installed then try again.

### Step 6: Read through the document in LyX
I've included a lot of LyX notes. They are in yellow boxes that say Note - click to open them up. thesis.lyx collects all the separate files together, click on the inputs or includes to open up the other files. If that makes no sense to you, read the multidoc tutorial (see Step 2).

### Step 7: Write your thesis
Add or remove files as you need, including them in thesis.lyx. You will be able to render and view each chapter individually as well. Good luck! There's no magic formula to writing a thesis except to just write it.
