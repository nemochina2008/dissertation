# phd_thesis

This repository is for drafting my PhD thesis at Duke University.

Here's the draft thesis rendered in various formats: for different purposes.

- [**html**](https://www.dropbox.com/s/jml6ybe4qa1x14k/thesis.html): quick web view
- [**docx**](https://www.dropbox.com/s/xzgsxaghxkrj5e6/thesis.docx): track changes with committee
- [**pdf**](https://www.dropbox.com/s/k1g47p1jejw8jk1/thesis.pdf): final grad school submission

The outputs are binary (vs text, including HTML which has embedded images and javascript), so the files were placed into Dropbox for download. The [Rmarkdown](http://rmarkdown.rstudio.com) files here are collated into a single [thesis.Rmd](./thesis.Rmd), which is most easily viewed through Github as markdown [thesis.md](./thesis.md). The pdf takes special handling to conform to the Duke Graduate School. See [make.R](make.R) for the details on how these individual Rmarkdown files are collated and rendered into these various forms.

Prefixes to Rmarkdown files (\*.Rmd) are simple letters for sorting front matter (a\_\*), core chapters (c\_\*) and back matter (x\_\*).

## Thesis Templates

- [UC Berkeley](https://github.com/stevenpollack/ucbthesis): uses Rmarkdown templates
- [Duke thesis](http://gradschool.duke.edu/academics/theses/): latex formatting specific to Duke

## Knitting the document

This thesis is being knitted into a scientifically reproducible document using the following techniques:

- **markdown**. [Rmarkdown](http://rmarkdown.rstudio.com).

- **citations**. Zotero and pandoc. Use better bibtex Zotero extension to enable drag-and-drop of citation into document in Pandoc format.



