В противоположность `flex-grow`, позволяет указать, насколько сильно элемент должен сжиматься, если суммарная ширина элементов превышает размер контейнера. Значение может быть любым положительным числом.

По умолчанию у всех дочерних элементов устанавливается значение этого свойства 1.

Элементы с ненулевым значением `flex-shrink` будут сжиматься, насколько это возможно, с учётом значений `flex-shrink` других элементов.

Если указать значение 0, то величина элемента останется равной `flex-basis`

Если flex-контейнер будет иметь свойство `flex-wrap: wrap` и `flex-basis` какого-то элемента окажется шире контейнера, то он сожмется до ширины контейнера при `flex-shrink: не 0`
