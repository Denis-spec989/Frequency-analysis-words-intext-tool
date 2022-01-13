# Приложение для частотного и количественного анализа английских слов в тексте
____
Приложение проводит частотный и количественный анализ английских слов и рассылает результат клиентам.
___
## Оглавление
1. [Описание приложения](#anchor1)
2. [Демо проекта](#anchor2)
3. [Используемые технологии в проекте](#anchor3)
4. [Техническое описание проекта](#anchor4)
___
<a id="anchor1"></a>
### 1.Описание приложения
Данное приложения было написано на open-source среде разработки **Apache Netbeans IDE** с использованием **JDK 16**. Настройка проекта будет указана в пункте [Техническое описание проекта](#anchor4).

**Цель проекта** - частотный анализ английских слов в тексте и рассылка результата клиентам.
___
<a id="anchor2"></a>
### 2.Демо проекта
**В папке с проектом находится файл readme.txt с нашим текстом.**

![avat](https://raw.githubusercontent.com/Denis-spec989/Frequency-analysis-words-intext-tool/master/assets/dem1.jpg)

**Задаем команду и название файла в Run->Arguments в настройках проекта**

![avat](https://raw.githubusercontent.com/Denis-spec989/Frequency-analysis-words-intext-tool/master/assets/dem2.jpg)

**Запускаем программу** 

![avat](https://raw.githubusercontent.com/Denis-spec989/Frequency-analysis-words-intext-tool/master/assets/scr2.jpg)
В консоли выводится число слов в тексте. 

num=1098.

Выводится сообщение , что клиент получил результат и сам результат.

Client get result=1098

Выводятся все слова по принципу слово - его частота в тексте.

![avat](https://raw.githubusercontent.com/Denis-spec989/Frequency-analysis-words-intext-tool/master/assets/scr1.jpg)
![avat](https://raw.githubusercontent.com/Denis-spec989/Frequency-analysis-words-intext-tool/master/assets/scr3.jpg)
___
### 3.Используемые технологии в проекте
<a id="anchor3"></a>
:heavy_check_mark: Библиотеки Java io и util
:heavy_check_mark: Java interface
:heavy_check_mark: Реализован паттерн publisher-subscriber
___
<a id="anchor4"></a>
### 4.Техническое описание проекта
Для анализа нам необходимо правильно ввести  строку в Arguments->Run проекта.

Команды и формат командной строки для работы с файлом.
```Java
System.out.println("формат ком.строки: имяПрограммы [-r<input-fileName>] [-w<output-fileName>]");
	System.out.println("   -?  показать Help файл");
	System.out.println("   -r  чтение из данного файла");
	System.out.println("   -w  выполнить вывод в указанный файл");
```
![avat](https://raw.githubusercontent.com/Denis-spec989/Frequency-analysis-words-intext-tool/master/assets/dem2.jpg)
Командная строка в аргументе -rreadme.txt означает чтение из файла readme.txt в директории, где лежит сам проект.

Остается лишь запустить программу.
___
Автор: Игнатов Денис
e-mail: proanglerdenis@gmail.com 


