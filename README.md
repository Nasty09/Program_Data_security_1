# Univerisy-Practice

## Задание

1. Выбрать любую RISC-платформу поддерживаемую эмулятором qemu: выбрать
архитектуру, выбрать эмулируемую платформу.
Архитектура: MIPS
Платформа: Malta

2. Собрать cross toolchain для этой архитектуры (можно воспользоваться
набором скриптов crosstool-ng)

3. Научиться использовать связку qemu + gdb (конфигурировать и запускать
эмулятор платформы Malta на базе qemu, запускать в ней программу под
отладчиком, устанавливать соединение с отладчиком в эмуляторе)

4. Изучить интерфейс программирования последовательного интерфейса на
эмулируемой платформе. Написать простейшую программу, выводящую в
последовательный интерфейс сообщение.

Далее "задачи со звездочкой", на случай, если вы быстро все освоите и
заходите двигаться дальше:

5. Научиться собирать и запускать в qemu ядро Linux с минимальным
окружением и взаимодействовать с ним.


6. Разработать модуль ядра. Модуль должен экспортировать интерфейс
символьного устройства и содержать переменную счетчик, которая
инкрементируется при каждом чтении из устройства. При каждом изменении
счетчика его значение должно выводиться в последовательный порт вместе с
ID последнего обратившегося процесса.

7. Разработать тестовое окружение, в котором несколько пользовательских
процессов одновременно читают из устройства.


Система сборки: gnu make. Разработку настоятельно рекомендуется вести в
Linux.
