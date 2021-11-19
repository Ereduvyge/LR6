# LR6
Лабораторная работа №6
#### Ход работы
Логин в аккаунт гитхаб. После этого установка гит и клонирование репозитория:
Настройка Git параметрами `git config --global user.name <username>` и `git config --global user.email <email>`.
Затем с помощью `git clone <url>` загрузил репозиторий.
После этого добавил в репозиторий файл "notmakingsence.txt" и с помощью `git pull` загрузил

![image](screenshots/1.png)

Далее с помощью команда `git log` запрашиваем историю изменений ветки, а с помощью `git checkout <name>` переключаемся между ветками

![image](screenshots/2.png)

![image](screenshots/3.png)

Далее пытаемся объеденить ветки masters и branch1 командой `git merge branch1`. Получаем ошибку и решаем с помощью  `nano <name`>, затем `git add <name>` и `git commit`

![image](screenshots/4.png)

![image](screenshots/5.png)

![image](screenshots/6.png)

Затем был произведене хард откат `git reset --hard <name>`

![image](screenshots/7.png)

Далее создал папку "Screenshots", которую поместил несколько скриншотов и добавил их в репозиторий, после чего сделал коммит и загрузил все на github

![image](screenshots/8.png)

После чего создал ветку report и файл "README.md", удалил ветку мастер и запросил логи в кратком формате

![image](screenshots/9.png)

Закончил отчет и загрузил обновил репозиторий на Github.
