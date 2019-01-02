# Awesome CV

> Inspired from the amazing project [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV)

## What is Awesome CV?

**Awesome CV** is LaTeX template for a **CV(Curriculum Vitae)**, **Résumé** or **Cover Letter** inspired by [Fancy CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv). It is easy to customize your own template, especially since it is really written by a clean, semantic markup.

## Preview the resume (using Docker)

#### Using Docker

```
$ docker run --rm  --name latex -v $PWD:/doc/ -it thomasweise/texlive xelatex.sh resume.pdf
```

## Github Cv assistant : Simple Pipeline compilation for your resume 🤖

To compile and Keep the resume up to date i advise to install the github Bot [gh-cv-assistant](https://github.com/olivierodo/gh-cv-assistant) on your repository.

[Gh-cv-assistant](https://github.com/olivierodo/gh-cv-assistant) will trigger the compilation at each push and create a new release containing the resume.pdf. Then you will just need to share the link of the latest tag on your different channels :  website, email, etc...

(ex : https://{your repo}/releases/download/latest/resume.pdf)
