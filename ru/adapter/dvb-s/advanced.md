#### Advanced

`MODULATION` - модуляция, возможные значения: `Default: Auto` (по умолчанию), `QPSK`, `QAM16`, `QAM32`, `QAM64`, `QAM128`, `QAM256`, `VSB8`, `VSB16`, `PSK8`, `APSK16`, `APSK32`, `DQPSK`. По умолчанию сейчас для DVB-S - QPSK, DVB-S2 - PSK8;

`FEC` - forward error correction (система корректирующих кодов), возможные значения: `Default: Auto` (по умолчанию), `NONE`, `1/2`, `2/3`, `3/4`, `4/5`, `5/6`, `6/7`, `7/8`, `8/9`, `3/5`, `9/10`';

`ROLL-OFF` - spectrum efficiency (коэфициент сглаживания), используется только для DVB-S2, возможные значения: Default: `35` (по умолчанию), `25`, `20`, `AUTO`;

`STREAM ID` - *Multistream filtering* - PLP stream ID, только для DVB-S2 и DVB-T2:  
   - `PLS MODE` - возможные значения: `Root`, `Gold`, `Combo`;
   - `PLS CODE` - возможные значения: `0 - 262143`;
   - `STREAM ID` - возможные значения: `0 - 255`;

`TIMEOUT` - *Delay in seconds before check DVR errors. Default 2 sec* - задержка в секундах до проверки DVR ошибок, по умолчанию 2 секунды;

`DDCI` - *Bind adapter to the DigitalDevices CI* - привязать адаптер к DVB-CI Digital Devices, значение соответствует номеру адаптера в системе;

`Budget Mode. Disable hardware PID filtering` - отключить аппаратную фильтрацию данных. Astra получит весь поток с DVB-адаптера. Параметр используется для передачи всего транспондера или для устаревших DVB-адаптеров без аппаратной фильтрации (например SkyStar 2). По умолчанию, аппаратная фильтрация включена;

`Signal in dBm` - вывод уровня сигнала в dBm. Для адаптеров TBS должен быть установлен параметр драйвера: options tbsfe dbm=1 esno=1 в файле /etc/modprobe.d/tbsfe.conf. DVB адаптеры с демодулятором CXD2820R передают значение уровеня сигнала в dBm по умолчанию;

`CA DELAY` - задержка, в секундах, перед отправкой информации о канале на модуль условного доступа.
