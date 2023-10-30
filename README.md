# О проекте
<div style="text-align: justify;">

**Изоконверсионное исследование кинетики твердофазных реакций** практическое руководство по обработке данных экспериментов ТГА + ДСК, являющееся логическим продолжением приложение по деконволюции пиков. В руководстве рассмотрены все популярные подходы к обработке экспериментальных данных и показан путь получения предсказаний.
</div>

# Реализованные методы
<div style="text-align: justify;">

+ Model fitting methods:
  - [X] Direct differential (DD)
  - [X] Coats-Redfern (CR)
+ Model-free (isoconversional) methods:
  + Differential methods:
    - [X] Friedman (FR)
  + Integral methods:
    + Approximated:
      - [X] Ozawa-Flynn-Wall (OFW)
      - [X] Kissinger-Akahira-Sunose (KAS)
      - [X] Starink (STR)
      - [X] Nonlinear integral method by Vyazovkin (VYZ)
    + Numerical:
      - [X] Advanced Isoconvertional method by Vyazovkin (AIC)
      - [X] Average linear integral method (ALIM)
+ Kinetic Compensation Effect (KCE)
+ f(α), g(α), Z(α) Master Plots

</div>

# Начало работы

## Предварительные требования

Прежде чем начать работу с этим проектом, убедитесь, что у вас установлен Python версии 3.11 и необходимые библиотеки. Все необходимые зависимости указаны в файле `requirements.txt`.

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone (https://github.com/kdavjd/isoconversion_study_of_reaction_kinetics)
2. Установите необходимые зависимости:
   pip install -r requirements.txt

## Настройка
1. Если Ваш датасет был получен через приложение деконволюции, то поместите его в 'src/TGA'. Иначе приведите файл в соответствие с готовыми примерами.
2. Откройте файл isoconversion_studyes.ipynb 
3. В первой ячейке, в константе ELEMENT, пропишите первые символы, с которых начинается файл Вашего датасета.

## Запуск
1. Запустите ноутбук.
2. При повторном расчете одного и того же файла экспериментов удаляйте папку 'kinetic_compensation_effect' из data.

# Авторы 
Проект создавался в сотрудничестве с моим коллегой- [Кузьминым Максимом Игоревичем](https://github.com/Xenozite)