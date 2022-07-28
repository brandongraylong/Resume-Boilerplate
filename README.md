# Resume-Boilerplate

## About
XeLaTeX boilerplate for resumes

## Dependencies
- [texlive-xetex (Debian)](https://packages.debian.org/sid/texlive-xetex)
- [watchexec (Github)](https://github.com/watchexec/watchexec)
- [Google Fonts](https://fonts.google.com/) - Place all of them under ./fonts/FONT_NAME

## Getting Started
- Add Google font to ./fonts/FONT_NAME
- Add custom colors for highlights and headings
- Create file resume.tex
- Copy over the boilerplate you want from boilerplate.tex
- See helpful commands to make it into a pdf

## Helpful Commands
- Create pdf once: `xelatex resume.tex`
- Watch and create pdf: `watchexec -w resume.tex xelatex resume.tex`
