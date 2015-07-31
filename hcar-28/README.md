# hcar-28

- [PDF][hcar-28-pdf]
- [HTML][hcar-28-html]

- Copy the `hcar-28-template.tex` template file:

  ```
  $ cp hcar-28-template.tex hcar-28-octohat.tex
  ```

- Add the project to the `makefile`. For example:

  ```
  hcar-28-octohat:
      latexmk -xelatex hcar-28-octohat.pdf
  ```

- Generate the document

  ```
  $ make hcar-28-octohat
  ```

  or

  ```
  $ make
  ```

  which generates all documents.

- Preview the document:

  ```
  $ open hcar-28-octohat.pdf
  ```

[hcar-28-pdf]: https://www.haskell.org/communities/05-2015/report.pdf
[hcar-28-html]: https://www.haskell.org/communities/05-2015/html/report.html
