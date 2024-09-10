UnrealCheatFinder - tool for search cheats/hacks/illegal tools on PC 
(For Counter-Strike 1.6,CS:Source,CS:GO,CS:2, tool like as wargods)

Support Windows XP - Windows 11

**Программа сканирует компьютер на следы установленных чит программ.**

**Возможности:**
1. Сканирование истории.
2. Сканирование реестра
3. Сканирование по файлам
4. Сканирование инжекта кода
5. Сканирование скрытого инжекта модулей
6. Обновляемая база данных читов автоматически загружается с github

Видео инструкция на русском языке : https://www.youtube.com/watch?v=PtZB7S9Y5do ( https://github.com/UnrealKaraulov/UnrealCheatFinderDB/tree/main/ru_video_help )

Используется так же как и wargods, но сохраняет результат в report.zip

Пользователи должны загружать сканер только с официального источника, с этого github репозитория.

Других официальных сайтов загрузки на данный момент не существует т.к есть вероятность подмены или заражения.

Проверка report.zip на отсутствие модификаций:
1. report.zip содержит папку с репортами, один на русском другой на английском языке
2. в папке с репортами есть файл md5.txt где содержится хэш соотвествующего репорта
( который можно проверить отправив соотвествующий репорт на сайт получения md5 файла из google.com или же получить его другими средствами )
3. время созданий всех файлов в архиве должно быть идентичным с временем запуска сканера (указано в report.txt)



**Процесс запроса сканирования:**
(так же как и wargods, но вместо ссылки на репорт игрок отправляет report.zip файл запросившему сканирование)
1. Администратор запрашивает у подозреваемого игрока прохождение проверки
2. Игрок загружает сканер последней версии с официального сайта для своей OS
3. Распаковывает, запускает с правами админа, ждет окончания сканирования
4. Передает администратору report.zip
5. Администратор рассматривает содержимое report.zip и выносит решение
   
(или же если идет демонстрация экрана, то администратор может читать информацию прямо из консоли и пункты 4 и 5 можно пропустить)



**Дополнительная информация:**
1. Данный сканер в отличии от UnrealDemoScanner ищет читы не в демо файле, а на ПК.
2. Сканер с закрытым исходным кодом
(иначе смысла нет, т.к все будут знать как прятать читы от него)
4. Сканер содержит всего 66 чит записей, и может не находить многие популярные паблик читы.
5. Сканер еще в бета тесте, по этому о проблемах (ложные детекты и т.п) сообщайте сюда на форум или в github.
6. Когда сканер будет обновлятся, старые версии не будут работать из-за несовместимости с базой данных
(учитывайте это если надумаете размещать сканер на посторонних ресурсах в обход рекомендациям, требуется загружать всегда актуальную версию сканера)
7. Я не рассказываю как пользоваться сканером персонально, вся информация уже имеется, если пользователь не умеет запускать сканер или администратор не может объяснить игроку как это сделать, это целиком ваши проблемы, читайте инструкцию.
(нужно понимать что не все умеют что-то скачивать с интернета или отправлять файлы, обучать игроков этому не входит в мои задачи, я только предоставляю инструмент для сканирования и данную инструкцию по пользованию)
8. Предложения и пожелания принимаются
9. Программа для создания собственной базы данных читов возможно будет опубликована в будущем.

**Примеры**

Вывод консоли версии UnrealCheatFinder 0.5

```
UnrealCheatFinder v0.5
File path:c:\Users\Karaulov\Downloads\ucf_win7\UnrealCheatFinder.exe
Current date and time:01/09/2024  16:34:21
Found Running Counter Strike with Steam: STEAM_0:1:46748090
Path: D:\SteamLibrary\steamapps\common\Half-Life\hl.exe
Process start time: 16:34:21
Latest used Steam:STEAM_0:1:46748090
Latest used Username:UZERNAM
Nickname from config.cfg: UZERNAM
You run this scanner without admins rights!
And scan result can be not fully.
Please run UnrealCheatFinder as admin, for detect more cheats on your PC
Cheat processed:66. Percent:100

Success! Scanned cheats count:66
Found 41 cheat entries!
Found "INTERIUM CRACK 2023" cheat!
Found "Pidor Wargods Cleaner" cheat!
Found "Sakura Hack" cheat!
Found "SteamID Changer" cheat!
Found "Furion v1.795" cheat!
Found "HPP CRACK 2023 [TG]" cheat!
Found "HPP HACK CRACK 2023" cheat!
Found "Alternative Hack [DATA]" cheat!
Found "Furion Cheat [DATA]" cheat!
Found "HPP LOADER" cheat!
Found "HPP DATA" cheat!
Found "Interium [DATA]" cheat!
Found "Putin Hack [DATA]" cheat!
Found "OXWARE HACK" cheat!
Found "FURION CHEAT [RX]" cheat!
Found "CHEAT WEBSITE DETECTED [IN DOWNLOADS]" cheat!
Found "CHEAT WEBSITE DETECTED [IN DESKTOP]" cheat!
Found 13 cheat entries previously launched in the system!
Found "FURION [REGISTRY]" cheat!
Found "EVOL HACK [REGISTRY]" cheat!
Found "OXWARE HACK [REGISTRY]" cheat!
Found "HPP LEAKED [SRC] [REGISTRY]" cheat!
Found "HPP HACK EXE [REGISTRY]" cheat!
Found "FURION [REGISTRY 2]" cheat!
Found "EVOL HACK [REGISTRY 2]" cheat!
Found "OXWARE HACK [REGISTRY 2]" cheat!
Found "HPP HACK EXE [REGISTRY 2]" cheat!
Found 13 cheats entries that were download on PC:
Found "FURION [HISTORY]" cheat!
Found "HPP HACK [1] [HISTORY]" cheat!
Found "HPP HACK [2] [HISTORY]" cheat!
Found "EXLOADER HACK [1] [HISTORY]" cheat!
Please copy report.zip scan result and send it to admins without modified! Please! ^_^
End scan time: 16:34:25

Press any key to exit...
```

Пример содержимого report.zip

Путь report.zip\^^REPORT^^\&''RU REPORT''__\report.txt
```
INI:
Текущая дата и время:01/09/2024  16:34:21
Обнаружена запущенная игра Counter Strike со Steam: STEAM_0:1:46748090
Путь к игре: D:\SteamLibrary\steamapps\common\Half-Life\hl.exe
Время запуска игры: 16:34:21
Последний используемый Steam:STEAM_0:1:46748090
Последний используемый никнейм:UZERNAM
Никнейм из конфига config.cfg: UZERNAM
Сканер запущен без прав администратора и не имеет доступа к некоторым директориям!
Найдено 41 следов установленных читов!
Найден чит INTERIUM CRACK 2023!
Найден чит Pidor Wargods Cleaner!
Найден чит Sakura Hack!
Найден чит SteamID Changer!
Найден чит Furion v1.795!
Найден чит HPP CRACK 2023 [TG]!
Найден чит HPP HACK CRACK 2023!
Найден чит Alternative Hack [DATA]!
Найден чит Furion Cheat [DATA]!
Найден чит HPP LOADER!
Найден чит HPP DATA!
Найден чит Interium [DATA]!
Найден чит Putin Hack [DATA]!
Найден чит OXWARE HACK!
Найден чит FURION CHEAT [RX]!
Найден чит CHEAT WEBSITE DETECTED [IN DOWNLOADS]!
Найден чит CHEAT WEBSITE DETECTED [IN DESKTOP]!
Найдено 13 следов читов которые запускались ранее в системе!
Найден чит FURION [REGISTRY]!
Найден чит EVOL HACK [REGISTRY]!
Найден чит OXWARE HACK [REGISTRY]!
Найден чит HPP LEAKED [SRC] [REGISTRY]!
Найден чит HPP HACK EXE [REGISTRY]!
Найден чит FURION [REGISTRY 2]!
Найден чит EVOL HACK [REGISTRY 2]!
Найден чит OXWARE HACK [REGISTRY 2]!
Найден чит HPP HACK EXE [REGISTRY 2]!
Найдено 13 следов читов которые скачивались на ПК!
Найден чит FURION [HISTORY]!
Найден чит HPP HACK [1] [HISTORY]!
Найден чит HPP HACK [2] [HISTORY]!
Найден чит EXLOADER HACK [1] [HISTORY]!
Конец репорта!
```
