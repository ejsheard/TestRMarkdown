# TestRMarkdown
A "Hello World" test drive of R Markdown


Using chapter 18 of https://happygitwithr.com/rmd-test-drive.html
Here is the official R Markdown documentation: http://rmarkdown.rstudio.com


Key pointers to take away:
- when you script analysis for sharing, render it to markdown, commit the .R, the .md, any associated figures, and push to GitHub. 
- This requires editing the YAML to "Use output: github_document" or to "keep_md: true" if you also want the output as html_document as well as a github md document
- Collaborators can then see the code but also browse the result without have to explicitly run the code in r. This makes the current state of your analysis more accessible e.g. from cell phone etc.


Workflow:
- set up new git project as usual e.g. Launch RStudio in a Project that is a Git repo that is connected to an already made GitHub repo (you will need the URL for this).
- open R Markdown file to work in: File > New File > R Markdown …
- then SAVE the R markdown file. The filename should end in .Rmd or .rmd. Save it in the top-level of this RStudio project and Git repository, that is also current working directory.
- You might want to commit here.
- Click on “Knit HTML” or do File > Knit Document. RStudio should display a preview of the resulting HTML. Also look at the file browser. You should see the R Markdown document, i.e. foo.Rmd AND the resulting HTML foo.html.
- Congratulations, you’ve just made your first reproducible report with R Markdown.
- You might want to commit here.
