# DJI-Phantom-3-4-driver-windows-10
Driver for DJI Phantom rc 3 / 4 for plugin to  windows 10 and play Simulator Liftoff and other

1.1 Version 05.02.2023 - create by RuCoder-team.

Main creater  - Maxim Smirnov

Idea and testing - Mihail Novgorodcev

source code - part - https://github.com/Matsemann/mDjiController 

this programe testing with  DJI GL300C controller ( Phantome 3/4 version)  and vjoy 2.0.5 and other new version .

Install on PC  windows 10 : 
1. Copy 2 files phantome_3_4_DJI_controller.exe  and vJoyInterface.dll  in any directory
2. install VJOY driver vJoy_205_080115.exe  or new from web
3. run and configure VJOY device - remember the device number  - 1 by default
4. plug-in your DJI controller on USB and turn it on
5. install teh drivers from dji  - dji_usb_5512_64_108.exe 
6. find and remember the COM port number of the controller - in windows "device manager" - his name "DJI USB Virtual COM (COM3 by default) 
7. run phantome_3_4_DJI_controller.exe and enter the port number( 3 by default) . enter  the number vjoy device(1 by default). And enter the 0 for view a log of chenged data from RC.
8. run VJOY monitor to testing to check that everything works,  move the sticks and you will see that they will also change in the monitor, so everything is ready to launch the simulator. Next, you need to configure the joystick in the simulator for yourself.

Done. Enjoy!!!

write questions to the email - moto4men@gmail.com (lang English or Russian)  

********************************************************************************************************************
Драйвер для DJI Phantom rc 3/4 (GL300C и других) для подключения к Windows 10 и тренировок в симулятоах Liftoff и других

1.1 Версия 05.02.2023 - создана командой RuCoder.

Главный создатель -   Максим Смирнов
Идея и тестирование - Михаил Новгородцев

исходный код - частично взят тут  - https://github.com/Matsemann/mDjiController

эта программа тестировалась с контроллером DJI GL300C (версия Phantome 3/4) и vjoy 2.0.5 и другими новыми версиями.

Установить на ПК Windows 10 :

1. Скопировать 2 файла phantome_3_4_DJI_controller.exe и интерфейс vJoy.dll в любом каталоге
2. установите драйвер VJOY vJoy_205_080115.exe или новое из Интернета
3. запустите и настройте устройство VJOY - запомните номер устройства - 1 по умолчанию
4. подключите контроллер DJI к USB и включите его
5. установите драйверы от dji - dji_usb_5512_64_108.exe
6. найдите и запомните номер COM-порта контроллера - в Windows "диспетчер устройств" - его имя "DJI USB Virtual COM (COM3 по умолчанию)
7. ЗАпустить phantome_3_4_DJI_controller.exe и введите номер порта (по умолчанию 3). введите номер устройства vjoy (по умолчанию 1) и далее введите 0 для просмотра журнала данных из RC(пульта).
запустите VJOY monitor для тестирования, чтобы проверить, что все работает, переместите стики пульта, и вы увидите, что они также изменятся в "vjoy мониторе", так что все готово к запуску симулятора. Далее вам нужно настроить джойстик в симуляторе под себя.
Сделано. Наслаждайтесь!!!

пишите вопросы на электронную почту - moto4men@gmail.com (на английском или русском языке)
