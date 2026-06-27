# tutorial_latex

LaTeX の習得用

## LaTeX を Ubuntu にインストール

```bash
sudo apt update
sudo apt install -y \
  texlive-latex-extra \
  texlive-lang-japanese \
  texlive-luatex \
  latexmk \
  biber
```

## VSCode 拡張

[LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) を使ってみる

デフォルト設定だとうまくいかない（lualatex を使ってくれない等）  
設定ファイルは [.vscode/settings.json](.vscode/settings.json) を参照
