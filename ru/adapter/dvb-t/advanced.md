#### Advanced

`MODULATION` - модуляция, возможные значения: `Default: Auto` (по умолчанию), `QPSK`, `QAM16`, `QAM32`, `QAM64`, `QAM128`, `QAM256`, `VSB8`, `VSB16`, `PSK8`, `APSK16`, `APSK32`, `DQPSK`;

`PLP ID` - PLP (Physical Layer Pipe) ID потока. Только для DVB-S2 и DVB-T2;

`BANDWIDTH` - ширина полосы, возможные значения: `Default: Auto` (по умолчанию), `6MHz`, `7MHz`, `8MHz`;

`GUARD` - guard interval length (длина защитного интервала), возможные значения: `Default: Auto` (по умолчанию), `1/32`, `1/16`, `1/8`, `1/4`, `1/128`, `19/128`, `19/256`;

`TRANSMIT` - modulation operation mode (FFT value)(режим работы модуляции), возможные значения: `Default: Auto` (по умолчанию), `1K`, `2K`, `4K`, `8K`, `16K`, `32K`;

`HIERARCHY` - использование иерархического кодирования (два транспортных потока на одной несущей), возможные значения: `Default: Auto` (по умолчанию), `NONE`, `1`, `2`, `4`;

`TIMEOUT` - *Delay in seconds before check DVR errors. Default 2 sec* - задержка в секундах до проверки DVR ошибок, по умолчанию 2 секунды;

`DDCI` - *Bind adapter to the DigitalDevices CI* - привязать адаптер к DVB-CI Digital Devices, значение соответствует номеру адаптера в системе;

`Budget Mode. Disable hardware PID filtering` - отключить аппаратную фильтрацию данных. Astra получит весь поток с DVB-адаптера. Параметр используется для передачи всего транспондера или для устаревших DVB-адаптеров без аппаратной фильтрации (например SkyStar 2). По умолчанию, аппаратная фильтрация включена;

`Signal in dBm` - вывод уровня сигнала в dBm. Для адаптеров TBS должен быть установлен параметр драйвера: options tbsfe dbm=1 esno=1 в файле /etc/modprobe.d/tbsfe.conf. DVB адаптеры с демодулятором CXD2820R передают значение уровеня сигнала в dBm по умолчанию;

`CA DELAY` - *Delay before initialize CA module. Default: 3 sec* - задержка, в секундах, перед отправкой информации о канале на модуль условного доступа;

`DVR BUFFER SIZE` - *DVR Buffer Size 1...200. Default: not set* - размер DVR буфера. Устанавливает значение DVR_BUFFER_SIZE = X * 10 * 188 * 1024 (не рекомендуется использовать).
