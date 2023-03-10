# Инструкция для работы с MarkDown

## ***Выделение текста***

Чтобы веделить текст курсивом необходимо обрамить его звездочками (*) или знаками нижнего подчеркивания (_). Напиример *вот так* или _вот так_

Чтобы выделить текст пулужирным необходимо обрамить его двойными звездочками (**) или двойным подчеркиванием (__). 
Например: 

**вот так** или __вот так__

Альтернативные способы выделения текста жирным или курсивом нужны для того чтобы мы могли совмещать оба этих способа. Например:

_текст может быть выделен курсивом и при этом быть **полужирным**_

Для зачеркнутого текста используются две тильды (~~).
Например:
 ~~Уберите это.~~

## ***Заголовки***

Чтобы выбрать размер заголовка нужно перед текстом поставить решетку (#). Например вот так:
# H1
## H2
### H3
#### H4
##### H5
###### H6

Кроме того, H1 и H2 можно обозначить подчеркиванием:

Alt-H1
======

Alt-H2
------
## ***Списки***

чтобы добавить ненумерованные списки необходимо выделить пункты звездочкой (*) или знаком (+). 
Например : 

* элемент (один) 1
* элемент (два) 2
* элемент (три) 3
+ элемент 4

Чтобы добавить нумерованные списки необходимо пункты просто пронумеровать.
Например: 

1. пункт один
2. пункт два
3. пункт три

## **Другой вариант**
    (В данном примере предшествующие и завершающие пробелы обозначены точками: ⋅)

    1. Первый пункт нумерованного списка
    2. Второй пункт
    ⋅⋅*Ненумерованный вложенный список.
    1. Сами числа не имеют значения, лишь бы это были цифры
    ⋅⋅1. Нумерованный вложенный список
    4. И еще один пункт.

    ⋅⋅⋅Внутри пунктов списка можно вставить абзацы с таким же отступом. Обратите внимание на пустую строку выше и на пробелы в начале (нужен по меньшей мере один, но здесь мы добавили три, чтобы также выровнять необработанный Markdown).

    ⋅⋅⋅Чтобы вставить разрыв строки, но не начинать новый параграф, нужно добавить два пробела перед новой строкой.⋅⋅
    ⋅⋅⋅Этот текст начинается с новой строки, но находится в том же абзаце.⋅⋅
    ⋅⋅⋅(В некоторых обработчиках, например на Github, пробелы в начале новой строки не нужны.)

    * Ненумерованный список можно размечать звездочками
    - Или минусами
    + Или плюсами

## *А выглядеть все будет вот так:*

1. Первый пункт нумерованного списка
2. Второй пункт
  * Ненумерованный вложенный список.
1. Сами числа не имеют значения, лишь бы это были цифры
  1. Нумерованный вложенный список
4. И еще один пункт.

   Внутри пунктов списка можно вставить абзацы с таким же отступом. Обратите внимание на пустую строку выше и на пробелы в начале (нужен по меньшей мере один, но здесь мы добавили три, чтобы также выровнять необработанный Markdown).

   Чтобы вставить разрыв строки, но не начинать новый параграф, нужно добавить два пробела перед новой строкой(..).  
   Этот текст начинается с новой строки, но находится в том же абзаце.  
   (В некоторых обработчиках, например на Github, пробелы в начале новой строки не нужны.)

* Ненумерованный список можно размечать звездочками
- Или минусами
+ Или плюсами
## ***Работа с изображениями***

Чтобы вставить изображение в текс, достаточно написать следующее:
![Привет это бэшка!](DSC02872-1024x683.jpg)

## ***Ссылки***

#### ***Ссылки можно оформить разными способами.***

    [Обычная ссылка в строке](https://www.google.com)

    [Обычная ссылка с title](https://www.google.com "Сайт Google")

    [Ссылка со сноской][Произвольный регистронезависимый текст]

    [Относительная ссылка на документ](../blob/master/LICENSE)

    [Для ссылок со сноской можно использовать цифры][1]

    Или можно просто вставить ссылку в квадратные скобки [текст ссылки]

    Произвольный текст, после которого можно привести ссылки.

    [произвольный регистронезависимый текст]: https://www.mozilla.org
    [1]: http://slashdot.org
    [текст ссылки]: http://www.reddit.com

### **А выглядеть будет так:**

#### ***Ссылки можно оформить разными способами.***

[Обычная ссылка в строке](https://www.google.com)

[Обычная ссылка с title](https://www.google.com "Сайт Google")

[Ссылка со сноской][Произвольный регистронезависимый текст]

[Относительная ссылка на документ](../blob/master/LICENSE)

[Для ссылок со сноской можно использовать цифры][1]

Или можно просто вставить ссылку в квадратные скобки [текст ссылки]

Произвольный текст, после которого можно привести ссылки.

[произвольный регистронезависимый текст]: https://www.mozilla.org
[1]: http://slashdot.org
[текст ссылки]: http://www.reddit.com

## ***Работа с таблицами***

*Таблицы не являются частью Markdown, но многие обработчики, например Markdown Here и Github, поддерживают их. Они позволяют легко добавить таблицы в электронное письмо -- в других случаях для этого нужно копировать их из другого приложения.*

    Вертикальные линии обозначают столбцы.

| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |

Внешние вертикальные линии (|) не обязательны и нужны только, чтобы сам код Markdown выглядел красиво. Тот же код можно записать так:

Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `так же` | **клево**
1 | 2 | 3
## ***Цитаты***
Блоки цитирования создаются с помощью символа (>), который нужно поставит перед предложением 

Например: 

> This is a blockquote. It is usually rendered indented and with a different background color.

Перевод:

> Это блок цитирования. Обычно он отображается с отступом и имеет другой цвет фона.

## ***Заключение и выводы***

Язык MarkDown богатый и насыщенный. Это облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).

Ничего сложного здесь нет. Нужно запастись терпением и все получится! :)

_"Дорогу осилит идущий"_
