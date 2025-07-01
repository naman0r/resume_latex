## My resume in LaTeX

build: `cmd option b`

builds the .pdf files in the out/ folder.

## how to replicate:

- clone this repo

```bash
source ~/.zshrc

# then add this to the file:

export PATH="/Library/TeX/texbin:$PATH"

# to open the file you can run this (mac, search up instructions for windows)

open -a TextEdit ~/.zshrc

```

- open your command palette on vscode (cmd shift p)

- search preferences: open user settings (JSON)

place this into the JSON file :

`"latex-workshop.latex.outDir": "./out"`

- what this does is make all the complile files go in the out folder

## now edit the main.tex file, or any .tex file.

once you have edited everything, run command option b. a .pdf file of the same name as your .tex file should show up in your /out folder. this is your resume!

credits: Jake's resume template from overleaf.
