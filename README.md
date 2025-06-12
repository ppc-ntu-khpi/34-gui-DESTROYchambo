# UI Lab 3
![](terminal-icon.png)
![](gui-icon.png)

Це одна з робіт, які доповнюють основний цикл лабораторних робіт #1-8 (проект **Banking**, [Netbeans](https://netbeans.org/)) з ООП.  Основна мета цих додаткових вправ - познайомитись з різними видами інтерфейсів користувача та засобами їх створення. Згадувані 'базові' роботи розміщено в [окремому репозиторії](https://github.com/liketaurus/OOP-JAVA) (якщо будете робити завдання на "4" або "5" раджу переглянути [діаграму класів](https://github.com/liketaurus/OOP-JAVA/blob/master/MyBank.png), аби розуміти які методи є у класів).

В ході першої роботи вам пропонується виконати **наступне завдання** - [Робота 3: GUI з Swing](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/blob/master/Lab%203%20-%20SWING/Lab%203.md)
  
**Додаткове завдання** (для тих хто зробив все і прагне більшого): [дивіться тут](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/blob/master/Lab%203%20-%20SWING/Lab%203%20-%20add.md)

Всі необхідні бібліотеки містяться у теці [jars](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/tree/master/jars). В тому числі - всі необхідні відкомпільовані класи з робіт 1-8 - файл [MyBank.jar](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/blob/master/jars/MyBank.jar). Файл даних лежить у теці [data](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/tree/master/data).

---
## На "трійку"
1. Завантажте jar-файл з усіма потрібними классами (*Bank, Customer, Account* та ін.) з наших попередніх лаб - [MyBank](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/blob/master/jars/MyBank.jar)
2. Створіть в Netbeans новий проект з назвою GUIdemo (або використайте проект, створений в ході виконання попередньої роботи). *УВАГА! Чекбокс *Create Main Class* треба **очистити** (**не створювати виконуваний клас**)!*
3. Додайте до проекту завантажену вами бібліотеку - правою кнопкой на проекті, обрати *Properties*, потім у дереві категорій обрати *Libraries* (другий пункт зверху), натиснути у правій частині вікна кнопку *Add JAR/Folder*, обрати jar-файл, завантажений у п. 1, натиснути *Ok*
4. Додайте до проекту файл **[SWINGdemo.java](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/blob/master/Lab%203%20-%20SWING/SWINGDemo.java)** з цього репозиторію
5. Вивчіть вихідний код у файлі, впевніться, що ви розумієте як він має працювати
6. Запустіть проект у звичайний спосіб. Ви маєте побачити вікно, в якому можна обрати одного з клієнтів банку, і натиснувши кнопку *Show*, побачити інформацію про нього. Продемонстрируйте результат викладачеві.

![](https://github.com/ppc-ntu-khpi/34-gui-DESTROYchambo/blob/0835f3013e9f4b6766dd613394fe2c7fd3f7188a/images/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-06-12%20144400.png)

## На "чотири"
1. Перепишіть код  так, щоб інформація про клієнтів банку та їх рахунки читалась з файлу **test.dat** (робота номер 8, [файл даних](https://github.com/ppc-ntu-khpi/GUI-Lab1-Starter/blob/master/data/test.dat) також є в цьому ж репозиторію)
2. При виборі клієнта має виводитись інформація про всі його рахунки!
3. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві.

## На "п'ять"
1. Додайте ще одну кнопку - *Report*, яка має виводити у нижній частині вікна звіт за клієнтами такого ж виду, як у роботі номер 8 (див. CustomerReport). 
2. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві.



[![Gitter](https://badges.gitter.im/PPC-SE-2020/OOP.svg)](https://gitter.im/PPC-SE-2020/OOP?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
![](https://img.shields.io/badge/Made%20with-JAVA-red.svg)
![](https://img.shields.io/badge/Made%20with-%20Netbeans-brightgreen.svg)
![](https://img.shields.io/badge/Made%20at-PPC%20NTU%20%22KhPI%22-blue.svg) 
