🇬🇧 [English README](https://github.com/Dellenoam/NotPixelBot/blob/master/README.md)

# NotPX Bot ⬛

Автоматизированный скрипт для NotPixel с рисованием на холсте по шаблону, прохождением proof-of-humanity проверок и многим другим

## Требования

[![Python](https://img.shields.io/badge/python-%3E%3D3.10-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D20.18.0-6DA55F?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/)

## Возможности

<table>
  <thead>
    <tr>
      <th>Функция</th>
      <th>Поддержка</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Супер-Мега-Крутое интро с капибарой</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Турнирное обновление</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Прохождение proof-of-humanity проверок</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Обнаружение изменений в API NotPixel</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Скрипт в .exe</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Простые скрипты для установки и удаления</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Привязка прокси к сессии</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Привязка User-Agent к сессии</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Автообнаружение новой .session и регистрация её в боте</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Авторисование</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Автоматические задания</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Автоматический ввод известных нам секретных слов</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Автоматический ввод ежедневных секретных слов</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Автоматический просмотр рекламы</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Автоматическое использование бомб</td>
      <td><img src="https://img.shields.io/badge/В_разработке-orange?style=flat-square" alt="X badge"></td>
    </tr>
    <tr>
      <td>Автоматический сбор PX</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Автоматическое улучшение бустеров</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Ночной режим</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Асинхронная работа</td>
      <td>✅</td>
    </tr>
  </tbody>
</table>

## Почему мы лучше других скриптов?

### ✨ Интро с капибарой (имба, киллер-фича)

![Интро с капибарой](https://github.com/Dellenoam/NotPixelBot/blob/master/assets/Capybara_Intro.gif)

### 🔍 Proof-of-Humanity проверки

Мы используем **реальные** решения задач для проверки на человечность, а не случайные ответы, чтобы вас не забанили.

Шанс быть забаненным все же есть, но мы сделали все возможное, чтобы предотвратить это.

### 🎨 Автоматическая покраска

Мы не используем случайные координаты для рисования на холсте. 

Наш скрипт автоматически рисует на холсте, используя шаблон и данные, полученные через WebSocket-соединение. Это означает, что вы будете получать PX за каждое рисование!

### 🌟 Простые скрипты для установки NotPixelBot и удаления

Мы предоставляем простые скрипты для удобной установки и удаления NotPixelBot.

### 🔗 Ясное использование реферальной системы

Если вы измените ref id на свой в настройках, то так оно и будет. Наш скрипт не препятствует этому, в отличие от некоторых публичных скриптов.

### 🚀 Регулярные обновления

Мы осуществляем регулярные обновления NotPixelBot в зависимости от изменений в NotPixel.

## [Настройки](https://github.com/Dellenoam/NotPixelBot/blob/master/.env-example)

<table>
  <thead>
    <tr>
      <th>Настройка</th>
      <th>Описание</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>API_ID / API_HASH</td>
      <td>Учетные данные API для Telegram API</td>
    </tr>
    <tr>
      <td>PLAY_INTRO</td>
      <td>True/False воспроизведение интро при запуске скрипта (НЕ СМЕЙ ЭТО ВЫКЛЮЧАТЬ)</td>
    </tr>
    <tr>
      <td>INITIAL_START_DELAY_SECONDS</td>
      <td>Диапазон задержки в секундах для случайной задержки при запуске сессии</td>
    </tr>
    <tr>
      <td>ITERATION_SLEEP_MINUTES</td>
      <td>Как долго скрипт будет ждать перед началом следующей итерации скрипта (рисование, клейм и т.д.)</td>
    </tr>
    <tr>
      <td>USE_REF</td>
      <td>True/False использование рефералки для запуска бота</td>
    </tr>
    <tr>
      <td>REF_ID</td>
      <td>Реферер ID для использования</td>
    </tr>
    <tr>
      <td>TOURNAMENT_TEMPLATE_ID</td>
      <td>ID турнирного шаблона</td>
    </tr>
    <tr>
      <td>SLEEP_AT_NIGHT</td>
      <td>True/False спать ночью</td>
    </tr>
    <tr>
      <td>NIGHT_START_HOURS</td>
      <td>Диапазон начальных часов ночи</td>
    </tr>
    <tr>
      <td>NIGHT_END_HOURS</td>
      <td>Диапазон конечных часов ночи</td>
    </tr>
    <tr>
      <td>ADDITIONAL_NIGHT_SLEEP_MINUTES</td>
      <td>Дополнительный диапазон минут для сна ночью</td>
    </tr>
    <tr>
      <td>ROUND_START_TIME_DELTA_MINUTES</td>
      <td>Дополнительные минуты после начала раунда</td>
    </tr>
    <tr>
      <td>ROUND_END_TIME_DELTA_MINUTES</td>
      <td>Дополнительные минуты до конца раунда</td>
    </tr>
    <tr>
      <td>CLAIM_PX</td>
      <td>True/False автоматический сбор px</td>
    </tr>
    <tr>
      <td>UPGRADE_BOOSTS</td>
      <td>True/False авто прокачка бустеров</td>
    </tr>
    <tr>
      <td>PAINT_PIXELS</td>
      <td>True/False авто рисование</td>
    </tr>
    <tr>
      <td>COMPLETE_TASKS</td>
      <td>True/False авто выполнение заданий</td>
    </tr>
    <tr>
      <td>PARTICIPATE_IN_TOURNAMENT</td>
      <td>True/False участие в турнире</td>
    </tr>
    <tr>
      <td>COMPLETE_QUESTS</td>
      <td>True/False авто ввод известных нам секретных слов</td>
    </tr>
    <tr>
      <td>COMPLETE_DANGER_TASKS</td>
      <td>True/False авто выполнение опасных заданий</td>
    </tr>
    <tr>
      <td>WATCH_ADS</td>
      <td>True/False просмотр рекламы</td>
    </tr>
  </tbody>
</table>

## Как установить 📚

Прежде чем начать, убедитесь, что вы соблюдаете [требования](#требования). Это очень ВАЖНО, без этого вы не сможете запустить наш скрипт.

### Получение ключей API

1. Перейдите на my.telegram.org и войдите, используя свой номер телефона.
2. Выберите "API development tools" и заполните форму для регистрации нового приложения.
3. Запишите полученные API_ID и API_HASH после регистрации вашего приложения в файл .env.

Иногда при создании нового приложения может отображаться ошибка. До сих пор не ясно, что является причиной, но вы можете попробовать решения, описанные на [stackoverflow](https://stackoverflow.com/questions/68965496/my-telegram-org-sends-an-error-when-i-want-to-create-an-api-id-hash-in-api-devel).

### Ручная установка на Linux

```shell
git clone https://github.com/Dellenoam/NotPixelBot.git
cd NotPixelBot
python3 -m venv .venv
source .venv/bin/activate
pip install poetry
poetry install --only main
cp .env-example .env
nano .env  # Укажите ваши API_ID и API_HASH, остальное берётся по умолчанию
```

### Ручная установка на Windows

```shell
git clone https://github.com/Dellenoam/NotPixelBot.git
cd NotPixelBot
python -m venv .venv
.venv\Scripts\activate
pip install poetry
poetry install --only main
copy .env-example .env
# Затем откройте .env в любом текстовом редакторе и укажите ваши API_ID и API_HASH, остальное берётся по умолчанию
```

### Установка на Windows с помощью скрипта powershell

ПРИМЕЧАНИЕ: Скрипт install.ps1 устанавливает Chocolatey, менеджер пакетов для Windows, и использует его для установки Python, Git и NodeJS, если они ещё не установлены

Мы также создали скрипт powershell, который позволяет легко установить NotPixelBot на Windows.

Перед запуском скрипта необходимо выполнить некоторую подготовку

Откройте powershell и введите там эту команду. Это позволит вам запускать скрипты без ограничений.

```shell
Set-ExecutionPolicy Unrestricted -Scope CurrentUser
```

Хорошо, теперь мы готовы. Выполните следующие команды:

```shell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/Dellenoam/NotPixelBot/refs/heads/master/windows_scripts/install.ps1" -OutFile "$env:TEMP\install.ps1"

powershell -ExecutionPolicy Bypass -File "$env:TEMP\install.ps1"
```

После этого скрипт будет загружен во временную папку и выполнен. Когда он попросит вас ввести путь, куда сделать git clone, просто введите путь, куда вы хотите сделать git clone. Например `C:\Users\username\Scripts\NotPixelBot` без кавычек.

Перейдите в папку с установленным ботом. Внутри нее скопируйте файле .env-example и переименуйте его в .env, а затем откройте его в любом редактори и пропишите в нем API_ID и API_HASH, что вы получили ранее.

Теперь вы можете перейти к разделу [Запуск скрипта](#запуск-скрипта).

### Удаление на Windows с помощью скрипта powershell

ПРИМЕЧАНИЕ: Скрипт install.ps1 устанавливает Chocolatey, который затем используется для установки Python, Git и Node.js. Этот скрипт uninstall.ps1 также удалит эти программы с помощью Chocolatey, включая сам Chocolatey. Однако он не удалит папку NotPixelBot. Поэтому, пожалуйста, будьте осторожны.

Если вы хотите удалить NotPixelBot, выполните следующие команды:

```shell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/Dellenoam/NotPixelBot/refs/heads/master/windows_scripts/uninstall.ps1" -OutFile "$env:TEMP\uninstall.ps1"

powershell -ExecutionPolicy Bypass -File "$env:TEMP\uninstall.ps1"
```

### Запуск скрипта

![NotPixel Intro](https://github.com/Dellenoam/NotPixelBot/blob/master/assets/NotPixel_Intro.gif)

#### Используя start.bat

Вы можете запустить скрипт используя start.bat скрипт, просто запустите его.

#### Вручную

Перед запуском скрипта вам ВСЕГДА нужно активировать виртуальное окружение и проверять на обновления.

```shell
# Linux
source .venv\bin\activate
# Windows
.venv\Scripts\activate

# Linux/Windows
git pull
```

Для запуска скрипта используйте `python3 main.py` на Linux или `python main.py` на Windows.

Также вы можете использовать флаг `--action` или `-a` для быстрого запуска скрипта с указанным действием.

```shell
# Linux
python3 main.py --action [1/2]
# Windows
python main.py --action [1/2]

# Или

# Linux
python3 main.py -a [1/2]
# Windows
python main.py -a [1/2]
```

Где [1/2] это:

    1 - Создаёт сессию
    2 - Запускает бота

Например, если вы хотите создать сессию, вы можете выполнить эту команду:

```shell
# Linux
python3 main.py --action 1
# Windows
python main.py --action 1

# Или

# Linux
python3 main.py -a 1
# Windows
python main.py -a 1
```

## Контакты

Если у вас есть вопросы или предложения, не стесняйтесь обращаться к нам в комментариях.

[![Capybara Society](https://img.shields.io/badge/Capybara%20Society-Присоединиться-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/capybara_society_ru)
