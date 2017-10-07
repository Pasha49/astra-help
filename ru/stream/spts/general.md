[Базовая настройка DVB-S/S2 адаптера][1]

[Базовая настройка SPTS][2]

## В ASTRA можно использовать различные источники приёма:

- [DVB](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#dvb), [ATSC](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#atsc), [ASI](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#asi)
- [HTTP (MPEG-TS, HLS)](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#http-mpeg-ts-hls)
- [UDP/RTP](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#udprtp)
- [RTSP](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#rtsp)
- [MPEG-TS файлы](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#mpeg-ts-файлы)

## Базовая настройка приёма SPTS:

- NAME - название потока;
- ID - идентификатор канала;
	- Multi Program Stream - мультиплекс с несколькими программами SPTS (Single Program Transport Stream - поток с одной программой);
	- Start stream on demand - автоматический старт вещания потока при запуске ASTRA;
- KEEP ACTIVE (Delay before stop stream if no active connections. Default: 0 (turn off immediately)) - задержка перед остановкой потока, если нет активных соединений, по умолчанию: 0 - выключать незамедлительно;
- INPUT LIST - список источников потоков;

	**NEW INPUT** - добавить дополнительный источник потока;
	 
	![Настройка SPTS источника приёма](http://b4.icdn.ru/s/slavabogu/5/56430645JuZ.jpg "Настройка SPTS источника приёма") - настройки основного источника приёма;
	
	- INPUT TYPE - выбор типа источника приёма:
	
	![Тип источника приёма](http://b4.icdn.ru/s/slavabogu/3/56431053iTx.jpg "Тип источника приёма")

	![Порядок SPTS источников приёма](http://b4.icdn.ru/s/slavabogu/6/56430646fUp.jpg "Порядок SPTS источников приёма") - выбор порядка основного и резервных источников приёма;
	 
- OUTPUT LIST - список передаваемых потоков;

	**NEW OUTPUT** - добавить дополнительный передающий поток;
	
	![Настройка SPTS передачи](http://b4.icdn.ru/s/slavabogu/5/56430645JuZ.jpg "Настройка SPTS передачи") - настройки основного потока передачи;

	- OUTPUT TYPE - выбор типа источника передачи;
	
	![Тип output источника](http://b4.icdn.ru/s/slavabogu/0/56431440GrC.jpg "Тип output источника")
	
	![Порядок SPTS потоков](http://b4.icdn.ru/s/slavabogu/6/56430646fUp.jpg "Порядок SPTS потоков") - выбор порядка основного и резервных выходных потоков;
	
	
	
### UDP/RTP

### DVB

### ATSC

### ASI

### HTTP (MPEG-TS, HLS)

### RTSP

### MPEG-TS файлы   
        
        
        

[1]: https://github.com/cesbo/astra-help/blob/master/ru/adapter/dvb-s/general.md "Базовая настройка DVB-S/S2 адаптера"
[2]: https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#%D0%91%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-spts-%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B0-%D0%B8%D1%81%D1%82%D0%BE%D1%87%D0%BD%D0%B8%D0%BA-dvb-ss2-%D0%B0%D0%B4%D0%B0%D0%BF%D1%82%D0%B5%D1%80
