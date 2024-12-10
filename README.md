# moderncv-template
Customized template of CV in LaTeX

This CV template is created by Christine P. Chai (cpchai21@gmail.com) from the ModernCV template (Xavier Danaux). The ModernCV package in LaTeX can be downloaded as below:
+ ModernCV template on GitHub: https://github.com/moderncv
+ ModernCV template on Overleaf: https://www.overleaf.com/latex/templates/moderncv-and-cover-letter-template/sttkgjcysttn

The original ModernCV template is awesome, and I use it for a wide variety of documents, such as resume/CV, cover letter, and even
project descriptions. Therefore, many settings need to be customized to meet my needs. I would like to share this CV template, which
includes the modifications I frequently use.

My **moderncv-template.tex** includes the following modifications:
+ Use the today command to show the date when I last modified this document.
+ Put the dates on the right hand side, instead of at the beginning of each row.
+ Add a contents section. This is recommended for a document with more than 10 pages.
+ Add the page number at the bottom right of each page.

Disclaimer: This template works best for long documents, such as a full CV or a file for all project descriptions. For industry job applications, it is still recommended to submit a one-page resume and be concise.

My **moderncv-with-input-files.tex** includes an additional change to the above:
+ Utilize the input command to add a section directly from another .tex file. When each section is long, this keeps the master document short and easy to maintain.

My **moderncv-cover-letter.tex** is another template for the cover letter:
+ Add the Firstname Lastname signature from an image file.

My **moderncv-app-stmt** is for writing application statements with multiple sections:
+ I used [https://www.lipsum.com/](https://www.lipsum.com/) to generate the dummy text.
