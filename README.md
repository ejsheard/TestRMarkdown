# TestRMarkdown
A "Hello World" test drive of R Markdown


Using chapter 18 of https://happygitwithr.com/rmd-test-drive.html


Key pointers to take away:
- when you script analysis for sharing, render it to markdown, commit the .R, the .md, any associated figures, and push to GitHub. 
- This requires editing the YAML to "Use output: github_document" or to "keep_md: true" if you also want the output as html_document as well as a github md document
- Collaborators can then see the code but also browse the result without have to explicitly run the code in r. This makes the current state of your analysis more accessible e.g. from cell phone etc.
