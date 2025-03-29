# WWISE-VOICE-WOT-BLITZ
Проект WWISE для создания озвучки экипажа в World of Tanks Blitz и Tanks Blitz

Этот проект позволяет создать собственную озвучку для игр World of Tanks Blitz и Tanks Blitz с использованием программы Audiokinetic WWISE.
Совместимая версия WWISE: 2019.2.9.7459.


# 1) Установка WWISE  
1. Скачайте WWISE Launcher с официального сайта (Пройдите процесс авторизации на сайте): https://www.audiokinetic.com/en/download/  
((( Примечание: Если при скачивании возникает ошибка 403 (блокировка IP из-за санкций): Включите любой VPN. )))  
((( Обновите страницу, нажмите Download — загрузка должна начаться. )))  
2. Установите WWISE Launcher после завершения загрузки.  
3. Запустите WWISE Launcher и пройдите процесс авторизации в программе.  
4. Откройте раздел WWISE.  
5. Перейдите к пункту INSTALL NEW VERSION.  
6. В кнопке Latest выберите: ALL.  
7. В кнопке Major Version выберите: 2019.2.  
8. В кнопке Version выберите: 2019.2.9.7459.  
9. Нажмите кнопку Install.  
((( Ожидайте полной установки (не отключайте VPN на этом этапе - если у вас блокировка IP из-за санкций). )))  
10. После установки в разделе INSTALLED VERSION появится версия 2019.2.9.7459.  
11. Справа от неё нажмите кнопку Launch Wwise (64-bit).  
((( Если у вас блокировка IP из-за санкций: Теперь VPN можно отключить — он больше не нужен. )))  

# 2) Подготовка проекта  
1. Откройте папку, куда был загружен скаченный ZIP файл.  
2. Распакуйте архив проекта WWISE VOICE WOT BLITZ в удобное место.  
3. Откройте папку распакованного архива  
4. Откройте файл WOTB_WWISE_VOICE.wproj двойным кликом.  
5. В интерфейсе WWISE перейдите в:  
Audio → Actor-Mixer Hierarchy → Default Work Unit → voice.  
6. В разделе voice вы увидите контейнеры для аудиофайлов. Каждый контейнер соответствует определённому действию:  
Примеры контейнеров:  
enemy_killed_by_player — противник уничтожен.  
fuel_tank_damaged — топливный бак повреждён.  
track_destroyed — гусеница сбита, движение невозможно.  
(все указания контейнеров в вверхней части по центру в окне с текстом)  
7. Нажмите на плюсик слева от контейнера, чтобы раскрыть его содержимое.  
Внутри находятся файлы-пустышки (например, в контейнере surveying_devices_functional есть файлы от surveying_devices_functional_01 до surveying_devices_functional_06 — всего 6 аудиофайлов).  
Как добавить свои аудиофайлы:  
7.1. Удалите файлы-пустышки.  
7.2. Вставьте свои аудиофайлы с точно такими же названиями (например, surveying_devices_functional_01.wav).  
7.3. Если нужно поменять задержку перед воспроизведением у каждого контейнера или аудио - используйте пункт Initial Delay. В проекте он установлен на 0.55  
7.4. Если нужно убрать лимит на количество файлов в контейнере:  
Переименуйте свои аудиофайлы перед вставкой, добавив дополнительные нули в название:  
Было: surveying_devices_functional_01.  
Стало: surveying_devices_functional_0001.  
Важно: Без лицензии можно добавить не более 200 аудиофайлов.  
7.5. Для увеличения лимита проекта:  
Вставьте ключ-лицензию в WWISE:  
PHByb2plY3QgaWQ9IjExMzI3IiBtYXNrPSJGQUlBOTUyOCIgZW5jPSIwIj48bGljZW5zZSBpZD0iMSIgbmFtZT0iV3dpc2UiIHR5cGU9IjMiIHBsYXRmb3Jtcz0iMiwzLDEwIiBleHBpcmVzPSIyMDIyLTA3LTAxIiAgLz48bGljZW5zZSBpZD0iMjEiIG5hbWU9Ik1haW50ZW5hbmNlIiB0eXBlPSIzIiBwbGF0Zm9ybXM9IjIsMywxMCIgZXhwaXJlcz0iMjAyMi0wNy0wMSIgIC8+PGxpY2Vuc2UgaWQ9IjIyIiBuYW1lPSJMZXZlbCBBIExpY2Vuc2UiIHR5cGU9IjMiIHBsYXRmb3Jtcz0iMiwzLDEwIiBleHBpcmVzPSIyMDIyLTA3LTAxIiAgLz48L3Byb2plY3Q+|Xwh9J1xhqrV4XhzXf3JemKSDHSX6qtRAyi/EIaVy07xSQvd+Svwfwx/rSt0viXRjl7uYvDUwmVLT1pFzU1Ogf+JmxiohdUAjnQ9YTTrT26uB+VSLH6X1y65HeRelqVZwypGK6ZjGCIw6Hjfbg+OehDtwr/BbRqN26zQXtgbJijvVfWWpdfS/2wM1b4Im6nL2u4OLU28lvXjnwjDSnb6Y0Brcq0HE1nDkljEy0XWmXWi05Uqo3Dqd5yd65WIX72riWkioi/cceU7ean+WGlrQzinffpAQb5LJry4uPWeLANTfbcR8lU9VNBYOSfAGqTNxh112HJGlmkaLE+fnkG0MQQ==  
Перед генерацией СаундБанка озвучки (в следующем разделе) временно измените системный год на 2021.  
После генерации верните актуальный год.  

# 3) Генерация озвучки
1. Перейдите в: SoundBanks → Default Work Unit.  
2. Щёлкните правой кнопкой по voiceover_crew → Generate Soundbank(s) for current platform.  
3. После генерации (даже если появится "Completed with error(s)") найдите файл:  
Путь: [Папка проекта]/GeneratedSoundBanks/Windows/English(US)/voiceover_crew.bnk.  
4. Конвертируйте файл voiceover_crew.bnk в формат .dvpl с помощью конвертера.  
  



# =========================  

# ally_killed_by_player
Уничтожение союзника вами
* ally_killed_by_player_01.wav
* ally_killed_by_player_02.wav

# ammo_bay_damaged
Повреждение боеукладки
* ammo_bay_damaged_01.wav
* ammo_bay_damaged_02.wav
* ammo_bay_damaged_03.wav

# armor_not_pierced_by_player
Броня не пробита
* armor_not_pierced_by_player_01.wav
* armor_not_pierced_by_player_02.wav
* armor_not_pierced_by_player_03.wav
* armor_not_pierced_by_player_04.wav
* armor_not_pierced_by_player_05.wav

# armor_pierced_by_player
Пробитие
* armor_pierced_by_player_01.wav
* armor_pierced_by_player_02.wav
* armor_pierced_by_player_03.wav
* armor_pierced_by_player_04.wav
* armor_pierced_by_player_05.wav
* armor_pierced_by_player_06.wav
* armor_pierced_by_player_07.wav
* armor_pierced_by_player_08.wav
* armor_pierced_by_player_09.wav
* armor_pierced_by_player_10.wav
* armor_pierced_by_player_11.wav
* armor_pierced_by_player_12.wav

# armor_pierced_crit_by_player
Попадание
* armor_pierced_crit_by_player_01.wav
* armor_pierced_crit_by_player_02.wav
* armor_pierced_crit_by_player_03.wav
* armor_pierced_crit_by_player_04.wav
* armor_pierced_crit_by_player_05.wav
* armor_pierced_crit_by_player_06.wav
* armor_pierced_crit_by_player_07.wav
* armor_pierced_crit_by_player_08.wav
* armor_pierced_crit_by_player_09.wav

# armor_ricochet_by_player
Рикошет
* armor_ricochet_by_player_01.wav
* armor_ricochet_by_player_02.wav
* armor_ricochet_by_player_03.wav
* armor_ricochet_by_player_04.wav
* armor_ricochet_by_player_05.wav
* armor_ricochet_by_player_06.wav
* armor_ricochet_by_player_07.wav

# commander_killed
Командир ранен
* commander_killed_01.wav
* commander_killed_02.wav
* commander_killed_03.wav

# driver_killed
Мех-Вод ранен
* driver_killed_01.wav
* driver_killed_02.wav
* driver_killed_03.wav

# enemy_fire_started_by_player
Враг горит
* enemy_fire_started_by_player_01.wav
* enemy_fire_started_by_player_02.wav
* enemy_fire_started_by_player_03.wav
* enemy_fire_started_by_player_04.wav

# enemy_killed_by_player
Противник уничтожен
* enemy_killed_by_player_01.wav
* enemy_killed_by_player_02.wav
* enemy_killed_by_player_03.wav
* enemy_killed_by_player_04.wav
* enemy_killed_by_player_05.wav
* enemy_killed_by_player_06.wav
* enemy_killed_by_player_07.wav
* enemy_killed_by_player_08.wav
* enemy_killed_by_player_09.wav

# engine_damaged
Двигатель повреждён
* engine_damaged_01.wav
* engine_damaged_02.wav
* engine_damaged_03.wav
* engine_damaged_04.wav
* engine_damaged_05.wav

# engine_destroyed
Двигатель выведен из строя
* engine_destroyed_01.wav
* engine_destroyed_02.wav
* engine_destroyed_03.wav

# engine_functional
Двигатель частично восстановлен, можно ехать
* engine_functional_01.wav
* engine_functional_02.wav

# fire_started
Танк горит
* fire_started_01.wav
* fire_started_02.wav

# fire_stopped
Пожар потушен
* fire_stopped_01.wav
* fire_stopped_02.wav
* fire_stopped_03.wav

# fuel_tank_damaged
Бак повреждён
* fuel_tank_damaged_01.wav
* fuel_tank_damaged_02.wav
* fuel_tank_damaged_03.wav
* fuel_tank_damaged_04.wav

# gun_damaged
Орудие повреждено
* gun_damaged_01.wav
* gun_damaged_02.wav
* gun_damaged_03.wav
* gun_damaged_04.wav

# gun_destroyed
Орудие выведено из строя, стрельба невозможна
* gun_destroyed_01.wav
* gun_destroyed_02.wav
* gun_destroyed_03.wav

# gun_functional
Орудие частично восстановлено, можно стрелять
* gun_functional_01.wav
* gun_functional_02.wav
* gun_functional_03.wav
* gun_functional_04.wav

# gunner_killed
Наводчик ранен
* gunner_killed_01.wav
* gunner_killed_02.wav
* gunner_killed_03.wav

# loader_killed
Заряжающий ранен
* loader_killed_01.wav
* loader_killed_02.wav

# radio_damaged
Рация повреждена
(НЕ ЗАДЕЙСТВОВАНА В ИГРЕ)[МОЖНО ПРОПУСТИТЬ]
* radio_damaged_01.wav
* radio_damaged_02.wav
* radio_damaged_03.wav
* radio_damaged_04.wav
* radio_damaged_05.wav

# radioman_killed
Радист ранен
(НЕ ЗАДЕЙСТВОВАНА В ИГРЕ)[МОЖНО ПРОПУСТИТЬ]
* radioman_killed_01.wav

# start_battle
Бой начинается
* start_battle_01.wav
* start_battle_02.wav
* start_battle_03.wav
* start_battle_04.wav
* start_battle_05.wav
* start_battle_06.wav
* start_battle_07.wav
* start_battle_08.wav

# surveying_devices_damaged
Приборы наблюдения повреждены
* surveying_devices_damaged_01.wav
* surveying_devices_damaged_02.wav
* surveying_devices_damaged_03.wav
* surveying_devices_damaged_04.wav
* surveying_devices_damaged_05.wav

# surveying_devices_destroyed
Приборы наблюдения выведены из строя
* surveying_devices_destroyed_01.wav
* surveying_devices_destroyed_02.wav
* surveying_devices_destroyed_03.wav
* surveying_devices_destroyed_04.wav
* surveying_devices_destroyed_05.wav
* surveying_devices_destroyed_06.wav

# surveying_devices_functional
Приборы наблюдения восстановлены
* surveying_devices_functional_01.wav
* surveying_devices_functional_02.wav
* surveying_devices_functional_03.wav
* surveying_devices_functional_04.wav
* surveying_devices_functional_05.wav
* surveying_devices_functional_06.wav

# track_cut
Гусеница сбита, можем откатиться
* track_destroyed_cut_01.wav

# track_damaged
Повреждение гусеницы
* track_damaged_01.wav
* track_damaged_02.wav
* track_damaged_03.wav
* track_damaged_04.wav

# track_destroyed
Гусеница сбита, движение невозможно
* track_destroyed_01.wav
* track_destroyed_02.wav
* track_destroyed_03.wav
* track_destroyed_04.wav

# track_functional
Гусеница восстановлена
* track_functional_01.wav
* track_functional_02.wav
* track_functional_03.wav
* track_functional_04.wav

# track_functional_can_move
Гусеница восстановлена, можно ехать
* track_functional_can_move_01.wav
* track_functional_can_move_02.wav
* track_functional_can_move_03.wav
* track_functional_can_move_04.wav
* track_functional_can_move_05.wav

# turret_rotator_damaged
Башня повреждена, скорость поворота башни снижена
* turret_rotator_damaged_01.wav
* turret_rotator_damaged_02.wav

# turret_rotator_destroyed
Башня выведена из строя, вращение невозможно
* turret_rotator_destroyed_01.wav
* turret_rotator_destroyed_02.wav

# turret_rotator_functional
Башня частично восстановлена, скорость вращения снижена
* turret_rotator_functional_01.wav
* turret_rotator_functional_02.wav

# vehicle_destroyed
Танк уничтожен
* vehicle_destroyed_01.wav
* vehicle_destroyed_02.wav
* vehicle_destroyed_03.wav

# =========================

# 4) Установка озвучки:  
  
🔹 Windows: 
1. Откройте папку с установленной игрой (World of Tanks Blitz или Tanks Blitz).  
2. Скопируйте файл voiceover_crew.bnk.dvpl в:  
Data/WwiseSound/[язык, например, ru].  
3. Подтвердите замену файлов.  
✅ Озвучка установлена!  
  -----------------------  
🔹 Android:  
📌 Подготовка в игре
1. Запустите World of Tanks Blitz или Tanks Blitz.
2. Перейдите в Настройки → Другое.
3. Включите "Загрузить все ресурсы игры" (если доступно).  
📌 Установка озвучки
4. Найдите папку с установленной игрой.  
5. Скопируйте файл voiceover_crew.bnk.dvpl в:  
- Клиент Wargaming: Android/data/net.wargaming.wot.blitz/files/packs/WwiseSound/[язык, например, ru].  
- Клиент Lesta Games: Android/data/com.tanksblitz/files/packs/WwiseSound/[язык, например, ru].  
⚠ Примечание: Начиная с Android 11, доступ к папке data может быть ограничен. Способы обхода зависят от устройства, ищите инструкции в интернете. 
6. Подтвердите замену файлов.  
✅ Озвучка установлена!  
 
  -----------------------  
Итог:  
Теперь у вас есть собственная озвучка для World of Tanks Blitz или Tanks Blitz!  
Желаю вам успехов в моддинге!  
Автор: Huntez  
  
Поддержать меня подпиской: https://youtube.com/HuntezChannel  
Поддержать меня финансово: https://donationalerts.com/r/Huntez  
