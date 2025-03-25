# GIT <img src="./assets/git-icon-logo-svgrepo-com.svg" width="40" height="40" alt="GIT logo"/>

Вітаю!✨

Цей репозиторій містить в собі вичерпний конспект, який я написала для себе, поки проходила курс Нікіти Тимошенка по [GIT та GITHUB](https://www.youtube.com/watch?v=9CnZihyYjjA&list=WL&index=2&t=1s)

Конспект створено у форматі питання-відповіді, щоб ви могли перевірити самі себе. Я старалась структурувати конспекти максимально наближено до структури курсу, щоб вам було легко орієнтуватися, які теми де можна продивитися і повторити

Також дуже раджу користуватися [конспектом до курсу](https://github.com/NickTimosh/git_course). Там дуже багато корисного: детальний опис команд, практичні завдання та багато корисних посилань

---

<h2>Зміст</h2>

<details>
    <summary>Командний рядок</summary>
    <ul>
        <li><a href="#command-line-terms">Командний рядок — терміни</a></li>
        <li><a href="#files-system-terms">Файлова система — терміни</a></li>
        <li><a href="#path-to-files">Шлях до файлів</a></li>
        <li><a href="#read-folder-content">Читання вмісту папок(команди)</a></li>
        <li><a href="#interaction-with-folders">Взаємодія з папками(команди)</a></li>
        <li><a href="#Командний рядок — взаємодія з файлами (команди)">Взаємодія з файлами(команди)</a></li>
    </ul>
</details>

<details>
  <summary>Git</summary>
  <ul>
    <li><a href="#git-overview">Короткий огляд</a></li>
  </ul>
</details>

<details>
  <summary>GitHub</summary>
  <ul>
    <li><a href="#">GitHub</a></li>
  </ul>
</details>

<h2>Комадний рядок</h2>

[Конспект](https://github.com/NickTimosh/git_course/blob/main/notebooks/1.%20%D0%92%D1%81%D1%82%D1%83%D0%BF%20%D0%B2%20%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%B8%D0%B9%20%D0%A0%D1%8F%D0%B4%D0%BE%D0%BA.md)

<h3 id="command-line-terms">Командний рядок — терміни</h3>

<details>
<summary>Що таке GUI?</summary>

-   графічний інтерфейс користувача (Graphical User Interface)
    -   спосіб взаємодії користувача з комп'ютером із використанням графічних елементів (вікна, кнопки і тд)

</details>

<details>
<summary>Що таке Сommand Line?</summary>

-   командний рядок
    -   текстовий інтерфейс для взаємодії з операційною системою
    -   простір, де вводяться текстові команди
    -   і тут же можуть викликатися і запускатися певні програми

</details>

<details>
<summary>Що таке термінал?</summary>

-   програма або інструмент, який надає доступ до командного рядка (вікно, куди команди вводяться)

</details>

<details>
<summary>Що таке Shell?</summary>

-   оболонка
    -   програма, яка виконує команди, введені у терміналі (інтерпретатор команд)

</details>

<details>
<summary>Принцип роботи Shell (схема)</summary>

<img src="./assets//images/working-principale-shell.png" width="800" alt="Schematic of the principle of shell operation"/>

</details>

<details>
<summary>Що таке Bash?</summary>

-   один із типів оболонок (Shell)
-   Bourne Again Shell (Bash)
-   підтримується у Windows через Git Bash

</details>

<details>
<summary>Взаємодія з ОС (схема)</summary>

<img src="./assets//images/interaction-with-OS.png" width="800" alt="Diagram of the stages of interaction with the operating system"/>

</details>

---

<h3 id="files-system-terms">Файлова система — терміни</h3>

<details>
<summary>Що таке каталог (директорія)?</summary>

-   структура, яка використовується для організації файлів у файловій системі

</details>

<details>
<summary>Що таке поточний каталог?</summary>

-   папка, в якій користувач перебуває прямо зараз
    -   команди по замовчуванню виконуються у поточному каталозі

</details>

<details>
<summary>Що таке батьківський каталог?</summary>

-   папка, що знаходиться на один рівень вища, за поточний

</details>

<details>
<summary>Що таке домашній каталог?</summary>

-   персональний каталог користувача
    -   Диск С —> Users —> User name (або USER)

</details>

<details>
<summary>Що таке кореневий каталог?</summary>

-   початкова точка файлової системи
    -   найвищий рівень ієрархії каталогів

</details>

<details>
<summary>Структура каталогів (схема)</summary>

<img src="./assets//images/directions-structure.png" width="800" alt="Directory structure"/>

</details>

---

<h3 id="path-to-files">Шлях до файлів</h3>

<details>
<summary>Що таке шлях (path)?</summary>

-   адреси файлів у каталозі файлової системи

</details>

<details>
<summary>Які є два види шляхів до файлів?</summary>

-   абсолютний
-   відносний

</details>

<details>
<summary>Де починається абсолютний шях?</summary>

-   з кореневого каталогу

</details>

<details>
<summary>Що визначає відносний шях?</summary>

-   розташування файлу по відношенню до поточного каталогу

</details>

<details>
<summary>Що таке розширення файлів?</summary>

-   частина назви файлу, що йде після крапки

</details>

<details>
<summary>Для чого потрібне розширення файлів?</summary>

-   для визначення типу файлу

</details>

---

<h3 id="read-folder-content">Командний рядок — читання вмісту папок (команди)</h3>

[Конспект](https://github.com/NickTimosh/git_course/blob/main/notebooks/2.%20git%20bash%20-%20%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B8.md)

[Практичні завдання](https://github.com/NickTimosh/git_course/blob/main/notebooks/3.%20git%20bash%20-%20%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B0.md)

<details>
<summary>Яка команда відображає вміст всієї папки, у якій знаходиться користувач?</summary>

-   ls

</details>

<details>
<summary>Яка команда дозволяє відобразити вміст каталогу відмінного від поточного?</summary>

-   ls `path` (вказати шлях)

</details>

<details>
<summary>Які типи шляхів це дозволяють?</summary>

-   обидва: відносний та абсолютний

</details>

<details>
<summary>Яка команда дозволяє повернути вмісти кореневого каталогу?</summary>

-   ls /

</details>

<details>
<summary>Яка команда дозволяє повернути вмісти батьківського каталогу?</summary>

-   ls ..

</details>

<details>
<summary>Яка команда очищає вікно терміналу?</summary>

-   clear

</details>

<details>
<summary>Як у Git Bash навігувати по командам, що вже були написані?</summary>

-   стрілочка вгору (до попередніх команд)
-   стрілочка вниз (до наступних команд, що були після попередніх)

</details>

<details>
<summary>Що таке прапорці команд?</summary>

-   додаткові опції команд

</details>

<details>
<summary>Як впроваджуються прапорці команд?</summary>

-   через дефіси, які ми пишемо після команди

</details>

<details>
<summary>Який прапорець надає довідку?</summary>

-   `комадна` --help

</details>

<details>
<summary>Яка команда дозволяє повернути вміст всіх папок у довгому форматі (з прапорцем)?</summary>

-   ls -l

</details>

<details>
<summary>Як вивести дані, які повертає команда у вигляді текстового файлу?</summary>

-   `your_command` > file_name.extension

</details>

<details>
<summary>Яка команда дозволяє вивести вміст папок у вигляді текстового файлу?</summary>

-   ls > `file_name.extension`
    -   наприклад, ls > output.txt

</details>

<details>
<summary>Яка команда дозволяє вивести вміст папок у вигляді текстового файлу у довгому форматі?</summary>

-   ls -l > `file_name.extension`
    -   наприклад, ls -l > output.txt

</details>

---

<h3 id="interaction-with-folders">Командний рядок — взаємодія з папками (команди)</h3>

[Конспект](https://github.com/NickTimosh/git_course/blob/main/notebooks/2.%20git%20bash%20-%20%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B8.md)

[Практичні завдання](https://github.com/NickTimosh/git_course/blob/main/notebooks/3.%20git%20bash%20-%20%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B0.md)

<details>
<summary>Яка команда показує поточну директорію?</summary>

-   pwd
    -   prind working directory

</details>

<details>
<summary>Що повертає ця команда?</summary>

-   шлях до каталогу, у якому ми знаходимось

</details>

<details>
<summary>Яка команда дозволяє змінити поточну директорію на домашній каталог користувача?</summary>

-   cd
    -   change directory

</details>

<details>
<summary>Як змінити поточну директорію на якусь конкретну іншу?</summary>

-   cd `path` (вказати шлях)

</details>

<details>
<summary>Яка команда повертає до батьківської директорії?</summary>

-   cd ..

</details>

<details>
<summary>Яка команда створює нову папку?</summary>

-   mkdir `directory_name`
    -   make directory

</details>

<details>
<summary>Як створити одразу кілька папок у поточній директорії?</summary>

-   mkdir `directory_name_1` `directory_name_2`
-   якщо потрібні вкладені каталоги:
    -   mkdir -p dir1/dir2/dir3

</details>

<details>
<summary>Яка команда дозволяє скопіювати директорію до певної папки?</summary>

-   cp -r `copy_directory to_directory`

</details>

<details>
<summary>Яка команда дозволяє видалити директорію?</summary>

-   rm -r `file_name` (рекурсивне видалення)
-   якщо директорія містить файли:
    -   rm -rf directory_name

</details>

---

<h3 id="interaction-with-files">Командний рядок — взаємодія з файлами (команди)</h3>

[Конспект](https://github.com/NickTimosh/git_course/blob/main/notebooks/2.%20git%20bash%20-%20%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B8.md)

[Практичні завдання](https://github.com/NickTimosh/git_course/blob/main/notebooks/3.%20git%20bash%20-%20%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B0.md)

<details>
<summary>Яка команда створює файл?</summary>

-   touch `file_name.extension`

</details>

<details>
<summary>Як команда дозволяє скопіювати файл і перенести його до іншої папки?</summary>

-   cp `copy_file destination_directory/`
    -   copy

</details>

<details>
<summary>Яка команда дозволяє записати щось у файл?</summary>

-   echo `print_something` > `in_file`

</details>

<details>
<summary>Яка команда дозволяє повернути вміст файлу?</summary>

-   cat `file_name`

</details>

<details>
<summary>Яка команда дозволяє видалити файл?</summary>

-   rm `file_name`

</details>

---

<h2>Git</h2>

<h3 id="git-overview">Git — короткий огляд</h3>
