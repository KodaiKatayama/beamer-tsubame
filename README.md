# beamer-tsubame

LuaLaTeX用のBeamerテーマです。

## 動作環境

- LuaLaTeX
- Noto Sans CJK JP
- NewComputerModernMath

## インストール

```bash
git clone https://github.com/KodaiKatayama/beamer-tsubame.git
cp beamer-tsubame/beamerthemetsubame.sty ~/texmf/tex/latex/beamer/
mktexlsr ~/texmf
```

## 使い方

```latex
\documentclass{beamer}
\usetheme{tsubame}
```