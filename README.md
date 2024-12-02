# Graph-Manager

## Опис проекту
**Graph-Manager** — це Java-додаток для створення та маніпуляції графами. Він дозволяє додавати та видаляти вершини й ребра, перевіряти їх наявність та виводити граф у зручному форматі.

### Основні класи
1. **Graph.java** — основний клас, що представляє граф. Реалізує основні операції з графом, включаючи додавання, видалення та перевірку вершин і ребер.
2. **Main.java** — демонстраційний клас, який показує використання функціоналу класу `Graph`.

### Як працює програма
1. **Додавання вершин та ребер**: можна додати вершину за допомогою методу `addVertex`, а ребро між двома вершинами за допомогою методу `addEdge`.
2. **Видалення вершин та ребер**: методи `removeVertex` і `removeEdge` дозволяють видаляти відповідні елементи графу.
3. **Перевірка існування**: методи `hasVertex` і `hasEdge` використовуються для перевірки наявності вершини чи ребра.
4. **Вивід графу**: метод `printGraph` друкує граф у вигляді списку суміжності.

### Функціональні можливості
- Додавання вершин (`addVertex(int vertex)`).
- Додавання ребер (`addEdge(int source, int destination)`).
- Видалення вершин (`removeVertex(int vertex)`).
- Видалення ребер (`removeEdge(int source, int destination)`).
- Перевірка існування вершин (`hasVertex(int vertex)`).
- Перевірка існування ребер (`hasEdge(int source, int destination)`).
- Вивід графу.

### Вимоги до системи
- Java 8 або вище.
- IDE для Java (IntelliJ IDEA, Eclipse, NetBeans або інший текстовий редактор з підтримкою Java).
