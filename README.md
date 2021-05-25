# Spark WSL
Configure a Spark environment within Windows Subsystem for Linux (WSL).

# Requirements
* [TexLive](https://www.tug.org/texlive)
  * In Ubuntu:
    ```bash
    sudo apt install texlive texlive-latex-extra latexmk
    ```
* [Pygments](https://pypi.org/project/Pygments) (via *Python*)
* Edit build process to escape terminal for *Minted*
  (see [settings.json](https://gitlab.com/tartagli0/spark-wsl/-/blob/master/.vscode/settings.json) file)

## For *Visual Studio Code* (*VS Code*)
* [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) plugin
* [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) plugin