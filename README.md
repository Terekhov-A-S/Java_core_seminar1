# Java Core (семинары)

![picture for project](https://raw.githubusercontent.com/Terekhov-A-S/Java_core_seminar1/main/src/main/resources/Java_core.jpg)

## Урок 1. Компиляция и интерпретация кода

### Задача 1.

Создать приложение с вложенностью пакетов не менее 3х, где будет класс для входа и несколько классов с логикой. Пример: приложение для внесения заметок во внешний файл с обязательной фиксацией времени. Пример:

*Введите заметку: Hello, world!*

*Дозапись в файл: 16.07.2023 -> Hello, world*

Скомпилируйте и запустите посредством CLI


#### Решение


1. Команда:

```cmd
javac -d out -sourcepath .\src\main\java\ .\src\main\java\Sample\Main.java
```

![picture command javac](https://raw.githubusercontent.com/Terekhov-A-S/Java_core_seminar1/main/src/main/resources/Javac.png)

2. Команда:

```cmd
java -classpath .\out Sample.Main
```

![picture command javac](https://raw.githubusercontent.com/Terekhov-A-S/Java_core_seminar1/main/src/main/resources/Java.png)

---


### Задача 2.

**(доп).** Создать два Docker-образа. Один должен компилировать Java-проект обратно в папку на компьютере пользователя, а второй забирать скомпилированные классы и исполнять их. Пример листинга для docker-compose приведен в презентации семинара


*Подготовил студент Geek Brains* [**`Терехов Александр`**](https://gb.ru/users/1db43d0f-6c3d-46d1-bf5e-974b49af6f0d), Java_core_seminar1
