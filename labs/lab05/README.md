# Лабораторная работа №5 — Таблицы в LaTeX

**Дисциплина:** Computer Skills for Scientific Writing  
**Автор:** Тесленко Кирилл Дмитриевич

## Материалы

- [LaTeX-исходник](src/tables.tex) — четыре примера таблиц;
- [Отчёт QMD](report/practical-scientific-writing-lab05-report.qmd);
- [Презентация QMD](presentation/practical-scientific-writing-lab05-presentation.qmd).

## Сборка

~~~bash
cd labs/lab05/src
xelatex -interaction=nonstopmode -halt-on-error tables.tex
xelatex -interaction=nonstopmode -halt-on-error tables.tex
~~~

Результат — `tables.pdf`. Второй проход необходим для обновления меток.

Для сборки отчёта и презентации из корня репозитория:

~~~bash
quarto render labs/lab05/report/practical-scientific-writing-lab05-report.qmd --to docx
quarto render labs/lab05/report/practical-scientific-writing-lab05-report.qmd --to pdf
quarto render labs/lab05/presentation/practical-scientific-writing-lab05-presentation.qmd --to revealjs
quarto render labs/lab05/presentation/practical-scientific-writing-lab05-presentation.qmd --to beamer
quarto render labs/lab05/presentation/practical-scientific-writing-lab05-presentation.qmd --to pptx
~~~

После публикации [GitHub Release v1.5.1](https://github.com/KirillUbuntu/Computer-Skills-for-Scientific-Writing/releases/tag/v1.5.1) содержит готовые форматы.

**Все числовые данные в примерах демонстрационные.**
