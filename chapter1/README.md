# 環境構築メモ

Juliaをローカル環境で動かすためのメモ

## インストール

[DOWNLOAD](https://julialang.org/downloads/)

## Jupyter notebook
jupyter notebookでjuliaが利用できるようになるための手順

1. まずjuliaをインストールしてREPLを起動する
2. REPLでパッケージモードを開いて```add IJulia```
3. Juliaモードに戻って```using IJulia```

## ターミナルから実行
PATHを通す必要があるので今回はアプリとしてインストールしているので以下を実行する．</br>
```sudo ln -s /Applications/Julia-1.5.app/Contents/Resources/julia/bin/julia /usr/local/bin/julia```