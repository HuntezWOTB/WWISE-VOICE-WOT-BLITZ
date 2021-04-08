# WWISE-VOICE-WOT-BLITZ
Исходный код проекта WWISE для создания озвучки экипажа к игре World of Tanks Blitz

Данный проект поможет сделать вам свою озвучку к игре World of Tanks Blitz с помощью программы Audiokinetic WWISE

Данный проект WWISE хорошо функционирует с версиями: 2019.2.9.7459 и 2019.2.10.7490

Как создать свою озвучку:
1) Скачиваем WWISE Launcher из официального сайта аудиодвижка
2) Устанавливаем WWISE Launcher
3) Запускаем WWISE Launcher
4) В WWISE Launcher выбираем пункт WWISE (второй с левого ряда)
5) В пункте INSTALL NEW VERSION из пункта Latest выбираем пункт All
6) Справа от All меняем 2021.1 на 2019.2
7) Справа от 2019.2 выбираем версию WWISE 2019.2.9.7459 или 2019.2.10.7490 (роли особой не играет)
8) После выбранной версии нажимаем снизу на кнопку Install...
9) После установки открываем Загрузки в Проводнике
10) Распаковываем WWISE VOICE WOT BLITZ проект полностью (лучше в удобное место)
11) Открываем двумя быстрыми кликами файл WOTB_WWISE_VOICE.wproj
12) После открытия открываем пункт Audio 
и открываем Actor-Mixer Hierarchy
Дальше открываем Default Work Unit
Теперь открываем voice и тут много контейнеров, в них мы должны вставить аудиофайлы, вот их список:
(К фразам идёт название аудиофайла и его формат, фразу сохраняем под нужным названием и форматом)
(Просто перенесите аудиофайл из папки в программу под нужный контейнер, она сама настроит его(если под правильным названием и форматом))

Уничтожение союзника вами
# ally_killed_by_player
ally_killed_by_player_01.wav
ally_killed_by_player_02.wav

Повреждение боеукладки
# ammo_bay_damaged
ammo_bay_damaged_01.wav
ammo_bay_damaged_02.wav
ammo_bay_damaged_03.wav

Броня не пробита
# armor_not_pierced_by_player
armor_not_pierced_by_player_01.wav
armor_not_pierced_by_player_02.wav
armor_not_pierced_by_player_03.wav
armor_not_pierced_by_player_04.wav
armor_not_pierced_by_player_05.wav

Пробитие
# armor_pierced_by_player
armor_pierced_by_player_01.wav
armor_pierced_by_player_02.wav
armor_pierced_by_player_03.wav
armor_pierced_by_player_04.wav
armor_pierced_by_player_05.wav
armor_pierced_by_player_06.wav
armor_pierced_by_player_07.wav
armor_pierced_by_player_08.wav
armor_pierced_by_player_09.wav
armor_pierced_by_player_10.wav
armor_pierced_by_player_11.wav
armor_pierced_by_player_12.wav

Попадание
# armor_pierced_crit_by_player
armor_pierced_crit_by_player_01.wav
armor_pierced_crit_by_player_02.wav
armor_pierced_crit_by_player_03.wav
armor_pierced_crit_by_player_04.wav
armor_pierced_crit_by_player_05.wav
armor_pierced_crit_by_player_06.wav
armor_pierced_crit_by_player_07.wav
armor_pierced_crit_by_player_08.wav
armor_pierced_crit_by_player_09.wav

Рикошет
# armor_ricochet_by_player
armor_ricochet_by_player_01.wav
armor_ricochet_by_player_02.wav
armor_ricochet_by_player_03.wav
armor_ricochet_by_player_04.wav
armor_ricochet_by_player_05.wav
armor_ricochet_by_player_06.wav
armor_ricochet_by_player_07.wav

Командир ранен
# commander_killed
commander_killed_01.wav
commander_killed_02.wav
commander_killed_03.wav

Мех-Вод ранен
# driver_killed
driver_killed_01.wav
driver_killed_02.wav
driver_killed_03.wav

Враг горит
# enemy_fire_started_by_player
enemy_fire_started_by_player_01.wav
enemy_fire_started_by_player_02.wav
enemy_fire_started_by_player_03.wav
enemy_fire_started_by_player_04.wav

Противник уничтожен
# enemy_killed_by_player
enemy_killed_by_player_01.wav
enemy_killed_by_player_02.wav
enemy_killed_by_player_03.wav
enemy_killed_by_player_04.wav
enemy_killed_by_player_05.wav
enemy_killed_by_player_06.wav
enemy_killed_by_player_07.wav
enemy_killed_by_player_08.wav
enemy_killed_by_player_09.wav

Двигатель повреждён
# engine_damaged
engine_damaged_01.wav
engine_damaged_02.wav
engine_damaged_03.wav
engine_damaged_04.wav
engine_damaged_05.wav

Двигатель выведен из строя
# engine_destroyed
engine_destroyed_01.wav
engine_destroyed_02.wav
engine_destroyed_03.wav

Двигатель частично восстановлен, можно ехать
# engine_functional
engine_functional_01.wav
engine_functional_02.wav

Танк горит
# fire_started
fire_started_01.wav
fire_started_02.wav

Пожар потушен
# fire_stopped
fire_stopped_01.wav
fire_stopped_02.wav
fire_stopped_03.wav

Бак повреждён
# fuel_tank_damaged
fuel_tank_damaged_01.wav
fuel_tank_damaged_02.wav
fuel_tank_damaged_03.wav
fuel_tank_damaged_04.wav

Орудие повреждено
# gun_damaged
gun_damaged_01.wav
gun_damaged_02.wav
gun_damaged_03.wav
gun_damaged_04.wav

Орудие выведено из строя
# gun_destroyed
gun_destroyed_01.wav
gun_destroyed_02.wav
gun_destroyed_03.wav

Орудие частично восстановлено, можно стрелять
# gun_functional
gun_functional_01.wav
gun_functional_02.wav
gun_functional_03.wav
gun_functional_04.wav

Наводчик ранен
# gunner_killed
gunner_killed_01.wav
gunner_killed_02.wav
gunner_killed_03.wav

Заряжающий ранен
# loader_killed
loader_killed_01.wav
loader_killed_02.wav

Рация повреждена
(НЕ ЗАДЕЙСТВОВАНА В ИГРЕ)[МОЖНО ПРОПУСТИТЬ]
# radio_damaged
radio_damaged_01.wav
radio_damaged_02.wav
radio_damaged_03.wav
radio_damaged_04.wav
radio_damaged_05.wav

Радист ранен
(НЕ ЗАДЕЙСТВОВАНА В ИГРЕ)[МОЖНО ПРОПУСТИТЬ]
# radioman_killed
radioman_killed_01.wav

Бой начинается
# start_battle
start_battle_01.wav
start_battle_02.wav
start_battle_03.wav
start_battle_04.wav
start_battle_05.wav
start_battle_06.wav
start_battle_07.wav
start_battle_08.wav

Приборы наблюдения повреждены
# surveying_devices_damaged
surveying_devices_damaged_01.wav
surveying_devices_damaged_02.wav
surveying_devices_damaged_03.wav
surveying_devices_damaged_04.wav
surveying_devices_damaged_05.wav

Приборы наблюдения выведены из строя
# surveying_devices_destroyed
surveying_devices_destroyed_01.wav
surveying_devices_destroyed_02.wav
surveying_devices_destroyed_03.wav
surveying_devices_destroyed_04.wav
surveying_devices_destroyed_05.wav
surveying_devices_destroyed_06.wav

Приборы наблюдения восстановлены
# surveying_devices_functional
surveying_devices_functional_01.wav
surveying_devices_functional_02.wav
surveying_devices_functional_03.wav
surveying_devices_functional_04.wav
surveying_devices_functional_05.wav
surveying_devices_functional_06.wav

Повреждение гусеницы
# track_damaged
track_damaged_01.wav
track_damaged_02.wav
track_damaged_03.wav
track_damaged_04.wav

Гусеница сбита, движение невозможно
# track_destroyed
track_destroyed_01.wav
track_destroyed_02.wav
track_destroyed_03.wav
track_destroyed_04.wav

Гусеница восстановлена
# track_functional
track_functional_01.wav
track_functional_02.wav
track_functional_03.wav
track_functional_04.wav

Гусеница восстановлена, можно ехать
# track_functional_can_move
track_functional_can_move_01.wav
track_functional_can_move_02.wav
track_functional_can_move_03.wav
track_functional_can_move_04.wav
track_functional_can_move_05.wav

Башня повреждена
# turret_rotator_damaged
turret_rotator_damaged_01.wav
turret_rotator_damaged_02.wav

Башня выведена из строя, вращение невозможно
# turret_rotator_destroyed
turret_rotator_destroyed_01.wav
turret_rotator_destroyed_02.wav

Башня частично восстановлена, скорость вращения снижена
# turret_rotator_functional
turret_rotator_functional_01.wav
turret_rotator_functional_02.wav

Танк уничтожен
# vehicle_destroyed
vehicle_destroyed_01.wav
vehicle_destroyed_02.wav
vehicle_destroyed_03.wav



Я думаю, вам это не составит труда. В проекте настроено всё (от задержки, до расстановки фраз в контейнеры[По ивентам])
После этой долго проделанной работы открываем пункт SoundBanks, в нём открываем Default Work Unit, в нём нажимаем правой кнопкой мыши по voiceover_crew
и нажимаем на пункт Generate Soundbank(s) for current platform
После завершения генерации будет результат Completed with error(s) с красным цветом текста, мы не обращаем на это внимания
Дальше мы открываем папку с проектом(куда вы её распаковали) и в нём открываем папку GeneratedSoundBanks дальше открываем Windows и в нём открываем English(US)
Внутри этой папки мы видим, что мы собрали озвучку, файл voiceover_crew.bnk и есть наша озвучка и мы её конвертором сделаем в формат dvpl

Для установки озвучки на стим клиент:
1) Узнаём, куда была установлена игра
2) Открываем папки: Data; WwiseSound; (Выбираем нужный нам язык, я выбираю папку ru) ru
3) В эту папку мы вставляем нашу озвучку (уже в формате dvpl) и подтверждаем замену файлов
Озвучка установлена!

Для установки на андроид:
1) Настройка в игре
1.1) Заходим в игру
1.2) После авторизации заходим в настройки
1.3) Выбираем раздел Другое
1.4) Включаем пункт "Загрузить все ресурсы игры" (если доступен)
2) Установка озвучки в файловом менеджере
2.1) (Необязательно)Если захотите вернуть озвучку, сделайте бэкап кэша
2.2) Копируем voiceover_crew.bnk.dvpl по пути:
(Копируем туда, куда были загружены файлы игры)
Android/data/net.wargaming.wot.blitz/files/packs/WwiseSound/(Выбираем нужный нам язык, я выбираю папку ru)ru
Именно в папку ru(на нужный нам язык) мы вставляем озвучку
Подтверждаем замену файлов
Озвучка установлена!


Я уверен, что вы смогли создать озвучку
Хочу вас попросить подписаться на мой ютуб канал Huntez: https://youtube.com/HuntezChannel
Если вы хотите отправить рубль(или другую валюту), то это вам сюда: https://donationalerts.com/r/Huntez

Желаю вам успехов в моддинге!
Автор: Huntez
