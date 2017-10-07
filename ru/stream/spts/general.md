[Базовая настройка DVB-S/S2 адаптера][1]

Базовая настройка SPTS потока, источник DVB-S/S2 адаптер:

- NAME - название потока;
- ID - идентификатор канала;
	- Multi Program Stream - мультиплекс с несколькими программами SPTS (Single Program Transport Stream - поток с одной программой);
	- Start stream on demand - автоматический старт вещания потока при запуске ASTRA;
- KEEP ACTIVE (Delay before stop stream if no active connections. Default: 0 (turn off immediately)) - задержка перед остановкой потока, если нет активных соединений (по умолчанию: 0);
- INPUT LIST - список приёмных потоков;
	- NEW INPUT - добавить новый приёмный поток;
- OUTPUT LIST - список отправляемых потоков;
	- NEW OUTPUT - добавить новый отправляемый поток.

# NEW INPUT

В ASTRA можно использовать различные источники:
- DVB, ATSC, ASI
- HTTP (MPEG-TS, HLS)
- UDP/RTP
- RTSP
- MPEG-TS Файлы

## DVB

## ATSC

## ASI

## HTTP (MPEG-TS, HLS)

## UDP/RTP

## RTSP

## MPEG-TS файлы

        
        
        
        

[1]: https://github.com/cesbo/astra-help/blob/master/ru/adapter/dvb-s/general.md "Базовая настройка DVB-S/S2 адаптера"
