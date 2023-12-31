    Директива выглядит как строка: "use strict" или 'use strict'. Когда она находится в начале скрипта, весь сценарий работает в «современном» режиме.
    
    AND (&&):

| A     | B     | A AND B |
| ----- | ----- | ------- |
| TRUE  | TRUE  | TRUE    |
| TRUE  | FALSE | FALSE   |
| FALSE | TRUE  | FALSE   |
| FALSE | FALSE | FALSE   |

OR (||):

| A     | B     | A OR B |
| ----- | ----- | ------ |
| TRUE  | TRUE  | TRUE   |
| TRUE  | FALSE | TRUE   |
| FALSE | TRUE  | TRUE   |
| FALSE | FALSE | FALSE  |

Условный (тернарный) оператор - единственный оператор в JavaScript, принимающий три операнда: условие, за которым следует знак вопроса (?), затем выражение, которое выполняется, если условие истинно, сопровождается двоеточием (:), и, наконец, выражение, которое выполняется, если условие ложно. Он часто используется в качестве сокращённого варианта инструкции if...else. 
        
        условие ? выражение1 : выражение2
    условие имеет выражение значения true или false
    выражение1 и выражение2 принадлежат любому типу
    
    Тернарная операция не подойдёт, если в зависимости от условия надо выполнить несколько (а не одно выражение) строчек кода (блок кода). Нужна условная конструкция if.

В JavaScript есть 8 основных типов данных.

    Семь из них называют «примитивными» типами данных:
        -number для любых чисел: целочисленных или чисел с плавающей точкой; целочисленные значения ограничены диапазоном ±(253-1).
        -bigint для целых чисел произвольной длины.
        -string для строк. Строка может содержать ноль или больше символов, нет отдельного символьного типа.
        -boolean для true/false.
        -null для неизвестных значений – отдельный тип, имеющий одно значение null.
        -undefined для неприсвоенных значений – отдельный тип, имеющий одно значение undefined.
        -symbol для уникальных идентификаторов.
        -object для более сложных структур данных.
        -Оператор typeof позволяет нам увидеть, какой тип данных сохранён в переменной.
        Имеет две формы: typeof x или typeof(x).Возвращает строку с именем типа. Например, "string".
        Для null возвращается "object" – это ошибка в языке, на самом деле это не объект.

alert
показывает сообщение.
prompt
показывает сообщение и запрашивает ввод текста от пользователя. Возвращает напечатанный в поле ввода текст или null, если была нажата кнопка «Отмена» или Esc с клавиатуры.
confirm
показывает сообщение и ждёт, пока пользователь нажмёт OK или Отмена. Возвращает true, если нажата OK, и false, если нажата кнопка «Отмена» или Esc с клавиатуры.

Строковое преобразование
Строковое преобразование происходит, когда требуется представление чего-либо в виде строки.

Например, alert(value) преобразует значение к строке.

Также мы можем использовать функцию String(value), чтобы преобразовать значение к строке:

