## Notice

This repository will never be updated. You can have access to the latest slides in the Typst version [here](https://github.com/02hyc/Group-Meeting-Typst).

## Group Meeting, theme Metropolis


## Intro

Weekly Report in Westlake University.


## Usage

The following code shows a minimal example of a Beamer presentation using
Metropolis.

```latex
\documentclass{beamer}
\usetheme{metropolis}           % Use metropolis theme
\title{A minimal example}
\date{\today}
\author{Matthias Vogelgesang}
\institute{Centre for Modern Beamer Themes}
\begin{document}
  \maketitle
  \section{First Section}
  \begin{frame}{First Frame}
    Hello, world!
  \end{frame}
\end{document}
```

Detailed information on using Metropolis can be found in the [manual][].

For an alternative dark color theme, please have a look at Ross Churchley's
excellent [owl](https://github.com/rchurchley/beamercolortheme-owl) theme.


## License

The theme itself is licensed under a [Creative Commons Attribution-ShareAlike
4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). This
means that if you change the theme and re-distribute it, you *must* retain the
copyright notice header and license it under the same CC-BY-SA license. This
does not affect the presentation that you create with the theme.


[demo slides]: http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/demo/demo.pdf
[manual]: http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/doc/metropolistheme.pdf
[CTAN]: http://ctan.org/pkg/beamertheme-metropolis
