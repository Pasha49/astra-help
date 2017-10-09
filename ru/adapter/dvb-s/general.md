#### General

`NAME` - имя адаптера;

`ID` - идентификатор адаптера, при создании нового адаптера генерируется автоматически, возможно использование своего ID;

`ADAPTER` - адаптер;

`TYPE` - тип адаптера, возможные значения:

   - Satellite: DVB-S, DVB-S2;  
   - Terrestrial: DVB-T, DVB-T2, ATSC, ISDB-T;  
   - Cable: DVB-C, DVB-C (Annex A), DVB-C (Annex B), DVB-C (Annex C), DVB-ASI;

`TRANSPONDER` - параметры транспондера:

   - FREQUENCY - частота несущей (950-13250 MHz);  
   - POLARIZATION - поляризация (Vertical, Horizontal, Right, Left);  
   - SYMBOLRATE - символьная скорость (1000-50000 Kbaud);

`Remove` - удаление адаптера и каналов.
