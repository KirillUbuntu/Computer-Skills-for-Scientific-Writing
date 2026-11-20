# Лабораторная работа №6 — Работа с библиографией

**Автор:** Тесленко Кирилл Дмитриевич  
**Дисциплина:** Computer Skills for Scientific Writing

## Материалы

- [База источников](src/references.bib)
- [natbib и BibTeX](src/natbib.tex)
- [biblatex и Biber](src/biblatex.tex)
- [Отчёт QMD](report/practical-scientific-writing-lab06-report.qmd)
- [Презентация QMD](presentation/practical-scientific-writing-lab06-presentation.qmd)
- [Готовые документы — релиз v1.6.1](https://github.com/KirillUbuntu/Computer-Skills-for-Scientific-Writing/releases/tag/v1.6.1)

## Сборка из корня репозитория

~~~bash
cd labs/lab06/src
pdflatex -interaction=nonstopmode -halt-on-error natbib.tex
bibtex natbib
pdflatex -interaction=nonstopmode -halt-on-error natbib.tex
pdflatex -interaction=nonstopmode -halt-on-error natbib.tex

pdflatex -interaction=nonstopmode -halt-on-error biblatex.tex
biber biblatex
pdflatex -interaction=nonstopmode -halt-on-error biblatex.tex
pdflatex -interaction=nonstopmode -halt-on-error biblatex.tex
~~~

Требуются pdfLaTeX, BibTeX, Biber, пакеты natbib, biblatex и кириллическая кодировка T2A. Результаты: `natbib.pdf` и `biblatex.pdf`.
