# My-CV

This is the CV modified from [Xu Cheng's template](https://github.com/xu-cheng/cv)

Download the [English version (2 pages)](./[2%20page(s)]%20shixi.chen.cv.pdf)

Download the [Chinese version (2 pages)](./[2%20page(s)]%20簡歷--陳世希.pdf)

## Environment

- TeXstudio 4.3.1 + MiKTeX 23.1 + MiKTeX-LuaTeX 1.16.0
- Font: [Noto Serif SC](https://fonts.google.com/noto/specimen/Noto+Serif+SC) for simplified chinese
- Font: [Noto Serif TC](https://fonts.google.com/noto/specimen/Noto+Serif+TC) for traditional chinese
- Font: [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC) for simplified chinese
- Font: [Noto Sans TC](https://fonts.google.com/noto/specimen/Noto+Sans+TC) for traditional chinese

## Compile

Please use `LuaTex` to compile and it is the only compiler that works for me

## Known Issues

This cannot be compiled using `PdfTex` of `XeTex`.

Using XeTex, it seems the "chinese-traditional" is not recognizable.
```
(C:\Users\schenax\AppData\Local\Programs\MiKTeX\tex/generic/babel/locale/zh\bab
el-chinese-traditional.tex)
Package babel Info: Importing data for chinese-traditional
(babel)             from babel-zh-Hant.ini. Reported on input line 22.
Package babel Info: Hyphen rules for 'chinese-traditional' set to \l@nil
(babel)             (\language81). Reported on input line 22.

! Undefined control sequence.
\\babelprovide ... \@nnil \else \bbl@luahyphenate 
                                                  \bbl@exp {\\\AddToHook {en...
l.22 ...rt, onchar=ids fonts]{chinese-traditional}
                                                  
The control sequence at the end of the top line
of your error message was never \def'ed. If you have
misspelled it (e.g., `\hobx'), type `I' and the correct
spelling (e.g., `I\hbox'). Otherwise just continue,
and I'll forget about whatever was undefined.
```
