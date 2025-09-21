# Compiled Research for 0xParc

### Contributors

- Volodymyr Borshch, Dash Fryer, Isabel Faulds, Isis Martinez, Abtin Olaee, Jeremie Park, Vincent Pangilinan, Aroonrassamee Wongkeaitaroon, Yan Zhang

### Editing tex

- install vs code extension LaTex Workshop, LaTex
- install Tex Live / MacTex & add to path
  - `brew install --cask mactex` on mac in homebrew
- in .tex , in vscode terminal `pdflatex 0xParc-Research.tex` , should be bound to ctrl + alt + b
- ctrl + alt + b after saving

### Converting tex to md

- install pandoc
  - `brew install pandoc` on mac in homebrew
- `pandoc 0xParc-Research.tex -o 0xParc-Research.md`
