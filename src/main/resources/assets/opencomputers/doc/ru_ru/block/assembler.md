# Сборщик роботов

![Harder, better, faster, stronger.](oredict:opencomputers:assembler)

Сборщик роботов - это продвинутая рабочая станция, позволяющая собирать такие сложные устройства, как [роботы](robot.md), [дроны](../item/drone.md) и [планшеты](../item/tablet.md). Они требуют для сборки большое количество энергии, поэтому рекомендуется использовать их совместно с [конденсатором энергии](capacitor.md).

Для создания устройства с помощью сборщика нужно вставить корпус устройства. Для [роботов](robot.md) это [системный блок](case1.md) любого уровня, а для [планшетов](../item/tablet.md) это [корпус планшета](../item/tabletCase1.md). Как и со всеми устройствами OpenComputers, компоненты должны быть помещены в указанные слоты, а при наведении курсора на слот подсвечиваются компоненты, которые можно туда вставить. Если у вас открыт NEI, совместимые компоненты также будут подсвечены в NEI.

Продолжайте вставлять все необходимые компоненты. Не забудьте про операционную систему или возможность установки ее позже (для роботов вы можете вставить [дисковод](diskDrive.md) для чтения [дискет](../item/floppy.md)). [EEPROM](../item/eeprom.md) большинства устройств может быть заменён после сборки, если поместить устройство и новый [EEPROM](../item/eeprom.md) в верстак. Старый [EEPROM](../item/eeprom.md) при этом будет возвращен вам в инвентарь.

Также [роботы](robot.md) могут иметь [монитор](screen1.md), для чего нужно установить в них [монитор первого уровня](screen1.md), а для возможности печатать на [мониторе](screen1.md) при сборке установите [клавиатуру](keyboard.md). У [планшетов](../item/tablet.md) [монитор](screen1.md) уже имеется в [корпусе планшета](../item/tabletCase1.md), но вы должны установить [клавиатуру](keyboard.md) для возможности печатать на [планшете](../item/tablet.md).

После того, как вы поместили все нужные компоненты, нажмите кнопку старта и дождитесь, когда устройство будет собрано и заряжено. Также стоит заметить, что вы *не* сможете изменить устройство после сборки. Если вы что-то забыли или допустили ошибку, придется разобрать устройство в [разборщике](disassembler.md), у которого есть шанс сломать некоторые составляющие предметы.

Наконец, о сложности: уровень предмета определяет, сколько пунктов сложности они будут требовать; компоненты первого уровня требуют 1 пункт сложности, второго уровня - 2 пункта, а третьего уровня - 3 пункта. Исключением являются улучшения-контейнеры, имеющие двойную сложность, например, [контейнеры апгрейдов](../item/upgradeContainer1.md) второго уровня требуют 4 пункта сложности. То же и для [контейнера карт](../item/cardContainer1.md)).
