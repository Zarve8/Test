# Житний Григорий - "MAELSTROM OF WAR"
# Пользовательские сценарий

### Группа: 10 - МИ - 3
### Электронная почта: gzhitniy@icloud.com
### VK: https://vk.com/id223946798

### [ Сценарий 1 - Запуск ]
1. При вызове программы(игры) запускается загрузчик и получает управление над пк
2. Создается новое окно, высвечивается заставка(логотип), в то время как догружаются все нужные файлы 
3. Высвечивается главное меню
4. Если пользователь выбирает"Find SErver" - запускается Сценарий 2
5. Если пользователь выбирает"Create Server" - запускается Сценарий 3
6. Если пользователь выбирает"Settings"- запускается Сценарий 5
7. Если пользователь выбирает"Exit" - программа завершается

### [ Сценарий 2 - Подбор игры ]
1. Игроку показывается список серверов: название сервера, карта, количество игроков
2. Игрок может выбирать будет идти поиск серверов локально или глобально по средством кнопки "Lan"
3. Игрок может обновить список нажав конопку "Refresh"
4. При нажатии на строку сервера игрок автоватически подключается к выбранному северу - запускается Сценарий 6 
5. При нажатии пользователем кнопки "Main menu" энтерфейс переход в состояние Сценарий 1-пункт3

### [ Сценарий 3 - Режим игры с ботами ]
1. Высвечивается окно с предложенными 'картами'
2. Пользователь выбирает карту на которой собирается играть
3. Пользователь выбирает сложность  "ботов"(от легких до опытных)
4. Пользователь выбирает название сервера
5. Пользователь выбирает максимальное число игроков
6. Если пользователь нажимает кнопку "Start" запускается Сценарий 6
7. При нажатии пользователем кнопки "Main menu" энтерфейс переход в состояние Сценарий1-пункт3

### [ Сценарий 4]
1. Высвечивается табло по краям экрано(игра продолжается, но управление отключено)
2. Слево высвечиваются соответсвующие иконки:
3. Если пользователь нажимает "Settings" то запускается Сценарий 5
4. Eсли пользователь нажимает "Continue" то продолжается Сценарий 6
5. Eсли пользователь нажимает "Exit" то запускается Сценарий 2

### [ Сценарий 5 - Настройки ]
1. Открывается меню настроек, кнопки "Ok", "Cancel", "Apply" и  соответсвующие вкладки:
2. "Keyboard" -  изменение кнопок управления
3. "Mouse" - изменение чувствительности мыши
4. "Audio" - изменение громкости звука и громкости музыки
5. "Video" - изменение разрешения и настройки уровня яркости

### [ Сценарий 6 - Раунд ]
0. Сервер самостоятельно модулирует спавн/поведение ботов(если они есть)
1. Пользователь 'респавница' на определенном участке карты
2. Если во время игры пользаватель наживает "Esc" - запускается Сценарий 4
3. Игрок может свободно передвигатся по карте и ипользовать и менять  вооружение 
4. В правом нижнем угле высвечивается доступное оружие и способности(если есть), отмечено используемое и количество патронов в         магазине и всего
   В левом нижнем углу эсть шкала здоровья а также его численный показатель
   В левом верхнем краю экрана высвечивается миникарта
   В середине счет и время до окнчания раунда
5. При попадании в противника ему наностится урон
6. Когда у игрок 'умирает' высвечивается экран смерти и отсчет времени, после 10 секунд игроку позволяется выбрать персонажа и запускается Сценарий 6
7. После окончания времени высвечивается счет и статистика каждого игрока, а также информацию о прогрыше/выйгрыше
8. Запускается Сценарий 2
