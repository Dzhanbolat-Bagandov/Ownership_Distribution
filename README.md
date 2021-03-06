# Ownership_Distribution
<h2>О приложении</h2>
<p>Данное приложение является реализацией решения задачи коллективного владения на языке Java.</p>
<h2>Суть задачи</h2>
<p>Имеется N объектов и M субъектов, M может быть как больше, равно,
так и меньше N. Каждый субъект может быть способным владеть некоторым
подмножеством из N (например N1, N2, N3) - SN. Каждый субъект в некоторый
момент времени может владеть некоторыми объектами из своего подмножества SN.
В каждый момент времени одним объектом может владеть только один субъект.
Задача заключается в том, чтобы максимально справедливо распределять владение
объектами между субъектами.</p>
<h2>Предлагаемый алгоритм</h2>

![Algorithm diagram](images/algorithm_diagram.png)

<h2>Использованные инструменты</h2>
<p>Сборка - Maven</p>
<p>Тесты - Junit 5</p>

<h2>Запуск тестов</h2>
<p>Тестовые классы расположены в пакете <b>src.test.java</b></br>
  Команда для запуска всех тестов: <code>mvnw test</code></br>
  Команда для запуска тестов из одного класса: <code>mvnw -Dtest=*имя_класса* test</code></br>
  Команда для запуска одного из класса: <code>mvnw -Dtest=*имя_класса*#*имя_метода* test</code></br>
</p>
<p>Интеграционный тест для <b>предоставленного примера</b> реализован в методе <code>MainTest.ProvidedTestCase()</code></br>
  Чтобы запустить его, используйте команду <code>mvnw -Dtest=MainTest#ProvidedTestCase test</code>
</p>
