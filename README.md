# Awesome CV

> Inspired from the amazing project [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV)

## What is Awesome CV?

**Awesome CV** is LaTeX template for a **CV(Curriculum Vitae)**, **Résumé** or **Cover Letter** inspired by [Fancy CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv). It is easy to customize your own template, especially since it is really written by a clean, semantic markup.

## Preview the resume (using Docker)

#### Using Docker

```
$ docker run --rm  --name latex -v $PWD:/doc/ -it thomasweise/texlive xelatex.sh olivier-rodomond.tex
```

## Github Action : Simple Pipeline compilation for your resume 🤖

Having is your resume on github is cool for the versioning but what is more fun is to automated it to be generated automatically at each commit !
It's the best way to keep you resume up to date, because the final PDF will be hosted on GITHUB :)

Look at the [Awesome-CV  Github Action](https://github.com/olivierodo/Awesome-CV-action)

I use it on this current repository, look at my configuration on [./.github/workflows/awesome-cv-ci.yml](./.github/workflows/awesome-cv-ci.yml) and that will generate an example like this  : https://github.com/olivierodo/Awesome-CV/releases/tag/latest where you can access the pdf easily.

[Awesome-CV  Github Action](https://github.com/olivierodo/Awesome-CV-action) will trigger the compilation at each push and create a new release containing the resume.pdf. Then you will just need to share the link of the latest tag on your different channels :  website, email, etc...(ex : https://{your repo}/releases/download/latest/resume.pdf)
