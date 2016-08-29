TaskView
========

По большому счёту, является контейнером для остальных отображений
и своей части, работающей с DOM, не имеет.

Сейчас при инициализации создаёт модели, обёртки и отображения, общие для
всех типов задач, и, затем, определив тип текущего задания, создаёт остальные
объекты, руководствуясь типом задания.

Определение типа задания происходит за счёт проверки наличия определённых
элементов в вёрстке страницы.

Элемент `.console` означает тип `javascript` или `javascript-challenge`.

Элемент `.task__goals` означает тип `simple` или `javascript`.