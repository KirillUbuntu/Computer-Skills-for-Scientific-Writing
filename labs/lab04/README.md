# Лабораторная работа №4

**Тема:** Включение графики в LaTeX.

- [Исходник рисунка TikZ](src/figure.tex)
- [Исходник с включением графики](src/graphics.tex)
- [Отчёт](report/practical-scientific-writing-lab04-report.qmd)
- [Презентация](presentation/practical-scientific-writing-lab04-presentation.qmd)

## Сборка

Из каталога labs/lab04/src:

```bash
pdflatex -interaction=nonstopmode -halt-on-error figure.tex
pdflatex -interaction=nonstopmode -halt-on-error graphics.tex
pdflatex -interaction=nonstopmode -halt-on-error graphics.tex
```

В результате формируются figure.pdf и graphics.pdf. Повторная компиляция graphics.tex обновляет перекрёстные ссылки.
