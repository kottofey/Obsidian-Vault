Изменение масштаба. Может принимать два аргумента -- по Х и по У

```css
transform: translate(X, Y)
```

Если указать только одно значение, то второе примет это же значение, то есть, объект измениться симметрично.

Если нужно изменить масштаб только по одной оси, то применяются свойства `scaleX` и `scaleY`.

Может принимать любое численное значение. За основу принимается 1. То есть, числа меньше единицы уменьшают объект, большие -- увеличивают.

![[scale.png]]

- `scale(0.5)` уменьшит объект в 2 раза;
- `scale(2)` увеличит объект в 2 раза;
- `scale(0)` полностью «схлопнет» объект, и его не будет видно;
- `scale(1)` оставит объект без изменений.

Если задавать отрицательные значения, то объект отзеркалируется
![[Pasted image 20240328000525.png]]
