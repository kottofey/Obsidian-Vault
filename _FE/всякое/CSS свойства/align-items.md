Выравнивает по высоте grid или flex-элементы по ***поперечной*** оси, не трогая их взаиморасположение. То есть, двигаются все элементы одновременно и в одном направлении.
#### Может принимать значения:
- `stretch` - значение по-умолчанию, элементы начинаются у верхней границы и занимают всю высоту (у флекса растягиваются на всю величину поперечной оси)
- `start` - элементы выстраиваются по верхней границы и если сожержимого немного, то не растягиваются на всю высоту
- `end` - аналогично start, но выстраиваются по нижней границе
- `center` - элементы располагаются по центру (для флекса сжимаются до сожержимого и располагаются по центру поперечной оси)

- `flex-start` - элементы сжимаютсяя до содержимого и располагаются у начала поперечной оси (по-умолчанию сверху)
- `flex-end` - элементы сжимаютсяя до содержимого и располагаются у конца поперечной оси (по-умолчанию снизу)
- `baseline` - элементы выравниваются по базовой линии