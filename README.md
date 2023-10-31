# О проекте
<div style="text-align: justify;">

**Изоконверсионное исследование кинетики твердофазных реакций**:
 практическое руководство по обработке данных экспериментов ТГА + ДСК, являющееся логическим продолжением приложение по деконволюции пиков. В руководстве рассмотрены все популярные подходы к обработке экспериментальных данных и показан путь получения предсказаний.
</div>

# Реализованные методы
<div style="text-align: justify;">

+ Модельные методы:
  - [X] Прямой дифференциальный
  - [X] Коутса-Редферна
+ Бзмодельные методы:
  + Дифференциальные методы:
    - [X] Фридмана
  + Интегральные методы:
    + Аппроксимационные:
      - [X] Озавы-Флина-Уолла (OFW)
      - [X] Киссенджера-Акахиры-Суносе (KAS)
      - [X] Старинка (STR)
      - [X] Вязовкина (VYZ)
    + Численные:
      - [X] Улучшенный Вязовкин (AIC)  
+ Компенсационный эффект (KCE)
+ f(α), g(α), Z(α) Мастер графики
+ Предсказания:
  + Дифференциальные методы:
    - [X] Уравнение Родюта
  + Интегральные методы:
    - [X] Уравнение Вязовкина
    - [X] Уравнение Фаршаса

</div>

# Начало работы

## Предварительные требования

Прежде чем начать работу с этим проектом, убедитесь, что у вас установлен Python версии 3.11 и необходимые библиотеки. Все необходимые зависимости указаны в файле `requirements.txt`.

## Установите необходимые зависимости
 ```bash
 pip install -r requirements.txt 
 ```

## Настройка
1. Если Ваш датасет был получен через приложение деконволюции, то поместите его в 'src/TGA'. Иначе приведите файл в соответствие с готовыми примерами.
2. Откройте файл isoconversion_studyes.ipynb 
3. В первой ячейке, в константе ELEMENT, пропишите первые символы, с которых начинается файл Вашего датасета.

## Запуск
1. Запустите ноутбук.
2. При повторном расчете одного и того же файла экспериментов удаляйте папку 'kinetic_compensation_effect' из data.

# Авторы 
Проект создавался в сотрудничестве с моим коллегой- [Кузьминым Максимом Игоревичем](https://github.com/Xenozite)