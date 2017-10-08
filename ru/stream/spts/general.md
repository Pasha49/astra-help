## SPTS:

- NAME - название потока;
- ID - идентификатор канала;
	- Multi Program Stream - мультиплекс с несколькими программами SPTS (Single Program Transport Stream - поток с одной программой);
	- Start stream on demand - автоматический старт вещания потока при запуске ASTRA;
- KEEP ACTIVE (Delay before stop stream if no active connections. Default: 0 (turn off immediately)) - задержка перед остановкой потока, если нет активных соединений, по умолчанию: 0 - выключать незамедлительно;
- INPUT LIST - список источников потоков;

	NEW INPUT - добавить дополнительный источник потока;
	 
	![Настройка ASTRA](http://b4.icdn.ru/s/slavabogu/5/56430645JuZ.jpg "Настройка ASTRA") - настройки основного источника приёма;
	
	- INPUT TYPE - выбор типа источника приёма:
	
	![Настройка ASTRA](http://b4.icdn.ru/s/slavabogu/6/56430646fUp.jpg "Настройка ASTRA") - выбор порядка основного и резервных источников приёма;
	 
- OUTPUT LIST - список передаваемых потоков;

	NEW OUTPUT - добавить дополнительный передающий поток;
	
	![Настройка ASTRA](http://b4.icdn.ru/s/slavabogu/5/56430645JuZ.jpg "Настройка ASTRA") - настройки основного потока передачи;

	- OUTPUT TYPE - выбор типа источника передачи;
	
	![Настройка ASTRA](http://b4.icdn.ru/s/slavabogu/6/56430646fUp.jpg "Настройка ASTRA") - выбор порядка основного и резервных выходных потоков;
______________________________________________________________________________________________________________________________________

## Примеры использования разных источников:

### UDP/RTP
___
### HTTP (MPEG-TS, HLS)
___
### RTSP
___
### MPEG-TS файлы
___
### ASI
___
### DVB

#### General

`NAME` - имя адаптера;

`ID` - идентификатор;

`ADAPTER` - адаптер;

`TYPE` - тип адаптера, возможные значения:

   - Satellite: DVB-S, DVB-S2;  
   - Terrestrial: DVB-T, DVB-T2, ATSC, ISDB-T;  
   - Cable: DVB-C, DVB-C (Annex A), DVB-C (Annex B), DVB-C (Annex C), DVB-ASI;

`TRANSPONDER` - параметры транспондера:

   - FREQUENCY - частота (950-13250 MHz);  
   - POLARIZATION - поляризация (Vertical, Horizontal, Right, Left);  
   - SYMBOLRATE - символьная скорость (1000-50000 Kbaud);  

#### LNB


