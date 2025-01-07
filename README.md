# Лабораторные работы по курсу:
## Методы, средства и технологии мультимедиа
Выполнил: Захаров В.А. группа М8О-408Б-21
## Выбранные датасеты

Классификация: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

Регрессия: https://www.kaggle.com/datasets/ikynahidwin/depression-student-dataset/data

## Результаты

<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация</td>
        <td>Acc=0.8641; Prec=0.8664; Rec=0.8641</td>
        <td>Acc=0.8696; Prec=0.8702; Rec=0.8696</td>
        <td>Acc=0.8696; Prec=0.8699; Rec=0.8696</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>MAE=0.1040; R²=0.7916</td>
        <td>MAE=0.0594; R²=0.7618</td>
        <td>MAE=0.0297; R²=0.8809</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация</td>
        <td>Acc=0.8533; Prec=0.8572; Rec=0.8533</td>
        <td>Acc=0.8696; Prec=0.8726; Rec=0.8696</td>
        <td>Acc=0.8587; Prec=0.8634; Rec=0.8587</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>MAE=0.2321; R²=0.6865</td>
        <td>MAE=0.2221; R²=0.7079</td>
        <td>MAE=0.2362; R²=0.6854</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация</td>
        <td>Acc=0.8043; Prec=0.8114; Rec=0.8043</td>
        <td>Acc=0.8696; Prec=0.8712; Rec=0.8696</td>
        <td>Acc=0.8750; Prec=0.8772; Rec=0.8750</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>MAE=0.0990; R²=0.6030</td>
        <td>MAE=0.0672; R²=0.6520</td>
        <td>MAE=0.1592; R²=0.6377</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация</td>
        <td>Acc=0.8859; Prec=0.8880; Rec=0.8859</td>
        <td>Acc=0.8859; Prec=0.8901; Rec=0.8859</td>
        <td>Acc=0.8858; Prec=0.9134; Rec=0.8858</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>MAE=0.1571; R²=0.7764</td>
        <td>MAE=0.2061; R²=0.6102</td>
        <td>MAE=0.2376; R²=0.2244</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация</td>
        <td>Acc=0.8804; Prec=0.8820; Rec=0.8804</td>
        <td>Acc=0.8859; Prec=0.8857; Rec=0.8859</td>
        <td>Acc=0.8967; Prec=0.8989; Rec=0.8967</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>MAE=0.2185; R²=0.7108</td>
        <td>MAE=0.1411; R²=0.7122</td>
        <td>MAE=0.1399; R²=0.5847</td>
    </tr>
</table>

Лучшие методы для классификации это: Градиентный бустинг, Случайный лес. Для регрессии это KNN.
