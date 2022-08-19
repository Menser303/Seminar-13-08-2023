# ЗАГОЛОВОК 
Для того того чтоб выделить заголовок необходимо поставить # слевой стороны  

## под заголовок работа с текстом.
для того что бы сделать под заголовок необходимо поставть ## диезы с левой стороны.



*Курсив.*
Для того чтобы сделать курсикв текст нужно выделить * с двух сторон или знаком _ с двух сторон на пример _вот так_ 

~~зачеркнутый текст~~ для того чтобы сделать зачеркнутый тест нужно выделить волнистым тире ~~ с двух сторон текст.

**Полужирный** 
Для того  чтобы сделать полу жирный тескт выделяем с двух строн ** звездачками тест или вот так __полужирный__ 

Алтернативные обозночения нужны для сешанного редактирования текста __то есть текст может быть выделен как полужирный *так и курсив.*__

## Виды списков 

Первый вид списков ставим через пробел слева одну звездочку * 
* Список 1
* Список 2 
* Список 3 

Второй вид списков ставим через пробел слева 1.  
1. список 1 
2. список 2
3. списко 3 

## Работа с изображениями 
Что бы вставить изображение в текст достаточно вставить следующее: 

![Шаба-дуб-таб](Rick%20Sanches.JPG)   

## Ссылки 

[GitHub](https://github.com)

## Работа с таблицами 

| первая колонка     | вторая колонка      | третья колонка      |
|--------------------|---------------------|---------------------|
| Информация ячейки 1| Информация ячейки 3 | Информация ячейки 5 |
| Информация ячейки 2| Информация ячейки 4 | Информация ячейки 6 |




# Команды для Git 

1. git init - позволяет сделать из папки систему репозитория 
2. git add '.\hello world.md' - команда добавления файл к отслеживанию программы (можно написать часть названия файла и нажать Tab)
3. git commit -m "save2" - сохранение текущего состояния файлов и сохранение коменнтариев к сохранению 

4. git diff - проверка различия файлов текущей версии с придыдущими
5. git log - журнал всех изменений.
6. git checkout  - переход к коментарию по его ID номеру из (git log) или же переход к отдельной ветке по ее названию.
7. git branch - обозначение позици ветки где находимся на данный момент 
8. git branch -d (название ветки) - удаление не нужной ветки 
9. git branch НАЗВАНИЕ ВЕТКИ - добовление новой ветки.
10. Clear - очистить реминал от ранее в веденой информации
11. git branch -m < oldname > < newname > — переименовать ветку.
12. .gitignore — текстовый файл, в котором задаются правила для исключения файлов из репозитория. Создается отдельно папка где к примеру хронятся картинки слева в колонке прописывается данная команда и туда складываем игнорируемые файлы.
13. git log --graph --decorate Флаг --graph рисует, основанный на тексте, график коммитов в левой части коммит-сообщений. --decorate добавляет имена веток или тегов, показанных коммитов. История комитов в виде дерева. Что бы выйти из набора команды жмем q.
14. git merge ( Название ветки ) - выполняет слияние отдельных направлений разработки, созданных с помощью команды git branch, в единую ветку. 
15. git clone ( ссылка для клонирования файла ) - позволяет скачать удаленный репозиторий с GitHub или любого другого удаленного хранилища, ресурса.
16.  git commit -a + enter - дабавит ьвсе измененные файлы в текущий коммит.
17. git branch -a - все ветки которые вообще существуют.
18. git branch -M master - назначение основной веткой master
19. git remote add origin https://github.com/Menser303/seminar-13-08-2022.git - добавление репозитория по сыылке после создания на акаунте удаленного доступа записи репозитория
20. git remote remove origin - перезапись уже ранее выложенного репозитория
21. git push origin master - выгрузка основной ветки на сервер GitHub
22. добавил информацию
23. git pull origin master - дозагрузка информации с изменениями с сайта или коллег которые правили файл.
24. cd - смена дириктории 






