## grid-template-areas
Если сетка grid сложная, то бывает проще описывать её не поколоночно и построчно, а целиком через области или `grid-template-areas`
Грид-областью называют часть сетки грид-контейнера, у которой может быть имя. Имя области придумывает сам разработчик. Оно должно начинаться с буквы и может включать цифры, дефис и знак подчёркивания. Например: header, section-2, user_avatar. Следует выбирать такие имена, которые описывают содержимое области.
Чтобы описать структуру грида с помощью областей, используют свойство grid-template-areas. В нём указывают имена грид-областей. При этом каждый ряд оборачивают в кавычки, а колонки разделяют пробелом. Если требуется растянуть область на несколько колонок, её имя повторяют нужное число раз.
	**ВАЖНО!** 
	*- Грид-области должны быть прямоугольными и непрерывными*
	*- При описании шаблона количество колонок в каждом ряду должно быть одинаковым!*
	*- Имена областей в одном контейнере должны быть уникальными*

![[grid05.svg]]
```css
grid-template-areas: "title title price"
                     "options description description"
                     "options disclaimer disclaimer";
```
![[grid-area]]
