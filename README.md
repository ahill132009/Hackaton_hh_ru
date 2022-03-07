# Hackaton_hh_ru

Comprtition link - https://boosters.pro/championship/HeadHunter/overview

## Задача
Автоматизация модерации отзывов пользователей о работодателях. Если отзыв проходит модерацию, ему назначается класс 0. Если отзыв не проходит модерацию, ему присваивается один или несколько классов от 1 до 8. Каждый класс обозначает причину отклонения отзыва. 

## Решение
Задача представляет собой решение проблемы multi-label классификации в рамках Natural Language Processing. Для решения задачи использовалась модель [rubert-tiny2](https://huggingface.co/cointegrated/rubert-tiny2)  
