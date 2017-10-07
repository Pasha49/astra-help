[Базовая настройка DVB-S/S2 адаптера][1]

## Базовая настройка SPTS потока, источник DVB-S/S2 адаптер:

- NAME - название потока;
- ID - идентификатор канала;
	- Multi Program Stream - мультиплекс с несколькими программами SPTS (Single Program Transport Stream - поток с одной программой);
	- Start stream on demand - автоматический старт вещания потока при запуске ASTRA;
- KEEP ACTIVE (Delay before stop stream if no active connections. Default: 0 (turn off immediately)) - задержка перед остановкой потока, если нет активных соединений (по умолчанию: 0);
- INPUT LIST - список приёмных потоков;
	- NEW INPUT - добавить новый приёмный поток;
- OUTPUT LIST - список отправляемых потоков;
	- NEW OUTPUT - добавить новый отправляемый поток.

## В ASTRA можно использовать различные источники:

- [DVB](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#dvb), [ATSC](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#atsc), [ASI](https://github.com/cesbo/astra-help/blob/master/ru/stream/spts/general.md#asi)
- HTTP (MPEG-TS, HLS)
- UDP/RTP
- RTSP
- MPEG-TS Файлы

### DVB

### ATSC

### ASI

### HTTP (MPEG-TS, HLS)

### UDP/RTP

### RTSP

### MPEG-TS файлы

## NEW OUTPUT     
        
        
        

[1]: https://github.com/cesbo/astra-help/blob/master/ru/adapter/dvb-s/general.md "Базовая настройка DVB-S/S2 адаптера"
