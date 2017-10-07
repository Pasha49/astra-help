[Базовая настройка DVB-S/S2 адаптера][1]

[Базовая настройка SPTS потока][2]

## В ASTRA можно использовать различные источники:

- [DVB](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#dvb), [ATSC](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#atsc), [ASI](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#asi)
- [HTTP (MPEG-TS, HLS)](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#http-mpeg-ts-hls)
- [UDP/RTP](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#udprtp)
- [RTSP](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#rtsp)
- [MPEG-TS файлы](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#mpeg-ts-файлы)

## Базовая настройка SPTS потока:

- NAME - название потока;
- ID - идентификатор канала;
	- Multi Program Stream - мультиплекс с несколькими программами SPTS (Single Program Transport Stream - поток с одной программой);
	- Start stream on demand - автоматический старт вещания потока при запуске ASTRA;
- KEEP ACTIVE (Delay before stop stream if no active connections. Default: 0 (turn off immediately)) - задержка перед остановкой потока, если нет активных соединений, по умолчанию: 0 - выключать незамедлительно;
- INPUT LIST - список источников потоков;

	NEW INPUT - добавить дополнительный источник потока;
	 
	![Настройка SPTS источника](http://b4.icdn.ru/s/slavabogu/5/56430645JuZ.jpg "Настройка SPTS источника") - настройки основного источника;
	
	- INPUT TYPE - выбор типа источника
	
	![Тип источника](http://b4.icdn.ru/s/slavabogu/3/56431053iTx.jpg "Тип источника")

	![Порядок SPTS источников](http://b4.icdn.ru/s/slavabogu/6/56430646fUp.jpg "Порядок SPTS источников") - выбор порядка основного и резервных источников;
	 
- OUTPUT LIST - список отправляемых потоков;

	NEW OUTPUT - добавить дополнительный отправляемый поток;
	
	![Настройка SPTS вещания](http://b4.icdn.ru/s/slavabogu/5/56430645JuZ.jpg "Настройка SPTS вещания") - настройки основного потока вещания;

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
