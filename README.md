This is a template for exporting edited highlight notes in Skim, a PDF annotation app for macOS, to a text file in markdown format. 

To use (MacOS): download the file and add it to ~/Library/Application Support/Skim/Templates (create the folder if it does not already exist).

# My workflow

I customised this template for my own use. I wanted a way of adding simple text annotations to highlighted quotations in a PDF, then exporting the annotated text en-masse to my note-taking system on Roam. My current solution is Skim plus this template, plus a specific workflow that indents my annotations (see below).

When taking notes on PDFs, I only use the 'highlight' functionality. I then edit the highlight directly (double click the highlight text in the Notes pane on Skim to edit), and I add my annotation after adding line breaks and Markdown-style indents manually (use ALT+ENTER/TAB to add line breaks and indentations in Skin)

# Examples

## The unedited text of a new highlight as it appears in Skim:
```
Teaching at Oxford is very different to most universities in the UK
```

## The same text after I've added my annotation (two line breaks, two indents and a hyphen added manually within the app):
```
Teaching at Oxford is very different to most universities in the UK

		- Here's example note number one.
```

## Formatted output text as it appears in Roam:**

**My Skim notes on 'freshers_study_guide_2020.pdf'**

p5, Teaching at Oxford is very different to most universities in the UK.
* Here's example note number one

p5, A study guide may also be provided by your Department or Faculty tailored to your subject needs: the Jesus College Freshers’ Study Guide is complementary to this information.
* Here's example note number two

p5, Each course at Oxford places a different emphasis on lectures, seminars, classes, practicals and individual teaching.
* Here's example note number three

# More information

Go to https://sourceforge.net/p/skim-app/wiki/Templates/ for more info and https://sourceforge.net/p/skim-app/wiki/Tips_and_Tricks/ for links to more templates.

This template is a modified verison of a template from https://github.com/semicolonsnet/skim-templates
