Какая-то информация 

Котики милые 
Инфа из ветки мастер
Арбузы бывают зеленые
Новая инфа из ветки пипипупу
Еще инфа из ветки пипипуп

Ветка пипипупу хочет конлфикта 
Мир никогда не входил в планы ветки мастер 

Эта строчка была добавлена в локальном репозитории. 
Эта инфа была добавлена в удаленном репозитории.


![hahahaha_cats](https://media.discordapp.net/attachments/578221595194294335/1047486691696447558/unknown.png?width=477&height=473)

Давайте внесем изменения на клоне от Николая)

##Инструкция по работе в git##

Для начала работы с git необходимо:

1. Установить git с помощью команды sudo pacman -S git

2. Установить и настроить программу Code OSS (yay -S VS_Code)

3. Создать папку в менеджере файлов

4. Зайти в Code OSS и выбрать созданную папку

5. В данной папке создать файл с расширением .md для дальейшей работы с текстовыми файлома с помощью языка Marckdown

6. Для инициализации git нужно открыть терминал из меню View и ввести команду git init

7. После инициализации нужно уточнить статус работы git с помощью команды git status

8. После введения необходимой информации нужно сохранить изменеия с помощью сочетания клавиш Ctrl+S

9. После сохранения изменений нужно ввести изменения в папку с репозиторием с помощью команды  git add (имя файла)

10. После внесения изменений необходимо создаьт коммит, с помощью команды git commit -m (комментарий к коммиту)

11. Вышеперечисленные действия можно выполнить одновременно, с помощью команды git commit -a

12. Для работы с ветками необходимо использовать комманду git branch. Сохдание ветки происходит по комманде git branch (название ветки).

13. Для переключения между ветками используется команда git checkout (название ветки)

14. Для просмотра изменений в коде нужно использовать команду git diff

Для совместной работы с git используется сайт GitHub.com. Он позволяет хранить репозитории не на локальном компьютере, а на сервере сайта. Удобен для работы нескольких сотрудников компании над одним проектом.


История создания git

Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.


Изначально Линус Торвальдс не использовал вообще никакой системы контроля версий. Люди, принимавшие участие в разработке ядра Linux, сначала должны были постить свои патчи в группе Usenet, а позже – отправлять по email. Все эти изменения Линус лично применял в своем дереве исходного кода. В итоге он выпускал новый релиз со всем этим деревом, без всякого разделения на какие-либо патчи. Единственным способом проследить историю этого процесса было изучение гигантского diff между двумя полными релизами.

Для графического отображения веток используется команда git log --graph.

#Работа с удаленным репозиторием#

Для начала работы с удаленным репозиторием необходимо привязать свой локальный репозиторий к репозиторию компании, в которой вы работаете, либо к своему удаленному репозиторию на GitHub или другом сервисе. Для этого необходимо следовать инструкциям, которые приводятся на GitHub. Для этого необходимо в терминале прописать команду _git remode add origin (URL удаленного репозитория на сервисе)_.

Для отправки внесенных в локальном репозитории изменений используется команда _git push_. *Перед отправкой необходимо сделать commit!*

При необходимости клонировать удаленный репозиторий в локальный используется команда _git clone (URL)_. Если нет необходимости клонировать полностью репозиторий, а необходимо просто получить информацию об изменениях в удаленном репозитории можно использовать команду _git pull_.

При отправке и скаичвании репозитория необходимо также указывать имя репозитория и ветку, в которую происходит отправка или скачивание.