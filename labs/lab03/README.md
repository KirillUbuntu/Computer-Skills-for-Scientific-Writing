# Лабораторная работа №3

**Дисциплина:** Computer Skills for Scientific Writing  
**Тема:** Набор математических формул в LaTeX  
**Студент:** Тесленко Кирилл Дмитриевич

## Цель
Освоить строчный и выключной математический режим, окружения `equation` и `align`, греческие символы и математические шрифты.

## Материалы
- [Исходный файл](src/math.tex)
- [Отчёт](report/practical-scientific-writing-lab03-report.qmd)
- [Презентация](presentation/practical-scientific-writing-lab03-presentation.qmd)

## Проверка
При установленном TeX Live:

```bash
cd labs/lab03/src
pdflatex -interaction=nonstopmode -halt-on-error math.tex
```

Успешная сборка создаст `math.pdf`. Для скринкаста требуется отдельно показать компиляцию и полученный PDF.

## Скринкаст
Ссылка на запись Rutube будет добавлена после публикации видео.
