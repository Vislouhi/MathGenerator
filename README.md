# MathGenerator

Полурабочий код в здесь (иногда не выпадает текст задачи):

https://github.com/Vislouhi/MathGenerator/tree/master/mathGenerator

Необходимо расширить набор случайных задач.

Готовые кодовые строки для генерации задач лежат здесь:

https://github.com/Vislouhi/MathGenerator/blob/master/mathGenerator/assets/js/tasks.js

## Пример строки для генерации текста задачи:

В $w1,магазине,сарае,гараже,...$ было $v1,1,2,3,...$ мешка с $w2,картошкой,морковкой,луком,...$. Из него забрали $v2,1,2,3,...$ мешков с $w2$.Сколко мешков осталось в $w1$?



Формат строки:

В $w1,магазине,сарае,гараже,...$ было |$v1,1,2,3,...$#$w2,мешок_мешка_мешков,ящик_ящика_ящиков,сумка_сумки_сумок$|

|15#слово_слова_слов| - эта запись означает, что слово нужно склонять, в зависимости от числа. Порядок вариантов склонений: одно слово, два слова, пять слов.

$[parameter],слово1,слово2,слово3...$ - запись указывает на то, что следует выбрать слово случайным образом. [parameter]=v1..v3,w1..w3.

v1 - v указывает на число, 1 идентификатор (нужен чтобы запомнить, какое число выбрано).

w1 - v указывает на слово, 1 идентификатор (нужен чтобы запомнить, какое слово выбрано).
