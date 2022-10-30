# LR6
Лабораторная работа №6
Создание копии в личное хранилище из https://github.com/Kurtyanik/LR6/.

![Создание копии в личное  хранилище](https://user-images.githubusercontent.com/115051008/198899405-02cca33e-a39b-4b54-b00a-b1ee81e3d7da.png)

Использование команд git config —global user.name и git config —global user.email для клиента Git и вывод своих данных из GitHub.

![Настройка клиента git](https://user-images.githubusercontent.com/115051008/198899455-17129018-c17f-47af-afb5-649219e06966.png)

Клонирование удаленного репозитория, используя команду git clone.

![Клонирование удалённого репозитория на компьютер](https://user-images.githubusercontent.com/115051008/198899498-f9ac95b0-d5c1-41a2-85dc-65de6fd97dc4.png)

Добавление файла через интерфейс GitHub. Далее переход в директорию LR6 командой cd LR6 для дальнейшей работы с файлами.

![Переход в директорию LR6](https://user-images.githubusercontent.com/115051008/198899521-1dba5303-7435-49bd-b5a5-ef3ab2bba61a.png)

Подтягивание изменения из веб-интерфейса GitHub для клиента Git с помощью команды git pull.

![Подтягивание изменений из веб-интерфейса GitHub для клиента Git](https://user-images.githubusercontent.com/115051008/198899544-c181f7e0-dff3-4c30-9fe8-a37a9f164757.png)

Просмотр коммитов ветки master, используя команду git log.

![Просмотр коммитов ветки master](https://user-images.githubusercontent.com/115051008/198899576-05a03135-941b-4183-a170-558af58dbc76.png)

Просмотр задержания ветки в текущем репозитории команды git branch.

![Просмотр задержания ветки в текущем репозитории](https://user-images.githubusercontent.com/115051008/198899588-0117c5ff-d025-4c22-a5ba-e5e27133dfa7.png)

Переход в ветку branch1 командой git checkout branch1.

![Переход в ветку branch1](https://user-images.githubusercontent.com/115051008/198899597-d417344b-439e-430e-ab9e-947e354bcc3c.png)

Просмотр коммитов ветки branch1 с помощью команды git log.

![Просмотр коммитов ветки branch1](https://user-images.githubusercontent.com/115051008/198899614-a94fb769-6355-4d53-8d52-90532acb0cb8.png)

Подробный просмотр коммитов с помощью команды git log -p.

![Подробное рассмотрение коммитов 1](https://user-images.githubusercontent.com/115051008/198899640-46f93a37-0cd6-4920-b044-03bf1a6882a9.png)

![Подробное рассмотрение коммитов 2](https://user-images.githubusercontent.com/115051008/198899647-5c05f418-79c9-43ea-9363-2f00ccbceacf.png)

Возвращение в ветку мастера.

![Возвращение в ветку мастера](https://user-images.githubusercontent.com/115051008/198899680-a8ec9077-c65f-402f-b10b-9e0f33e1d0dd.png)

Выполнение слияния в ветке master, используя команду git merge branch1.

![Выполнение слияния в ветку master](https://user-images.githubusercontent.com/115051008/198899725-c65c679a-4e89-4bb3-ba75-1aae6ca0f28b.png)

Из-за того, что файл mergefile.txt не отслеживается используется команда git status для отображения состояния рабочего каталога.

![Отображение состояния рабочего каталога и раздела проиндексированных файлов](https://user-images.githubusercontent.com/115051008/198899767-b248195a-8770-4283-a482-93296fb22792.png)

Добавление файла для создания git add mergefile.txt.

![Добавление файла для создания](https://user-images.githubusercontent.com/115051008/198899804-8b69e482-a6f1-4bfc-a4d6-7be069d057f4.png)

Проверка отслеживания файла.

![Проверка отслеживания файла](https://user-images.githubusercontent.com/115051008/198899847-59c06b87-ba96-44c1-a1b8-52464b81a943.png)

После разрешения конфликта оставляем коммит при помощи команды git commit -m "Ветки".

![Оставление коммита](https://user-images.githubusercontent.com/115051008/198899973-c24ce1b4-ad8b-48cb-825f-c7557e3e9402.png)

Удаление побочной ветки после успешного слияния при помощи команды git branch -d branch1

![Удаление побочной ветки после успешного слияния](https://user-images.githubusercontent.com/115051008/198900024-12f31604-ef94-4e3f-9f7c-5107b7044cb6.png)

Создание текстовых файлов и комментариев для них через терминал. При создании текстов используется команда echo hello > change1.txt, зафиксируем его git add change_1.txt. Написание комментария с помощью команды git commit -m "Change_1.txt". Повторение алгоритма еще раз, название публикации - change_2.txt.

![Создание текстовых файлов и комментариев для них в терминале](https://user-images.githubusercontent.com/115051008/198900080-4fcb5088-b6ca-4523-af5f-a27bcdeaf66d.png)

Просмотр комментариев, исользуя команду git log.

![Просмотр комментариев](https://user-images.githubusercontent.com/115051008/198900215-c3d4671e-3fa8-40f0-a88c-5da96b1760d2.png)

Создание "хард" отката коммита. Ввод git reset —hard HEAD~1

![Указание харда для отката коммита](https://user-images.githubusercontent.com/115051008/198901015-f107d4fd-e98c-41b3-ba4a-b7b982b694ae.png)

Создание ветки для отчета и переход в git branch report.

![Создание ветки для отчёта и переход в неё](https://user-images.githubusercontent.com/115051008/198901040-3a4950b1-5446-4c2e-8880-be521e71d2af.png)

Получившаяся итоговая история операций.

![Получившаяся итоговая история операций](https://user-images.githubusercontent.com/115051008/198901150-54eaa735-50ab-426c-a026-034bac33254a.png)

В конце работы необходимо отправить все локальные изменения в сетевое хранилище GitHub командой git push.
