#  Task One. 
## Ответьте письменно на вопросы:

_Тестовые заглушки  позволяют изолировать компоненты системы для тестирования. Это помогает убедиться, что каждый модуль работает правильно независимо от других._   

_Если нужно проверить, что метод был вызван с определенными аргументами, можно использовать мок заглушки._

```
// Создаем мок-объект
List mockedList = mock(List.class);

// Используем мок-объект
mockedList.add("one");
mockedList.clear();

// Проверяем, что методы были вызваны с правильными аргументами
verify(mockedList).add("one");
verify(mockedList).clear();
```

_Если нужно вернуть определенное значение или исключение в ответ на вызов метода, можно использовать мок заглушки. Они предоставляют предопределенные ответы на вызовы методов._
_Для имитации взаимодействия с внешним API или базой фейки._

