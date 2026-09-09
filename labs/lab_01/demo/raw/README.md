# Происхождение исходных файлов

Файлы в этой папке - неизменяемая локальная копия официально опубликованных данных NYC Taxi & Limousine Commission.

| Локальный файл. | Официальный URL. | Размер. | SHA-256. |
| --- | --- | ---: | --- |
| `green_tripdata_2025-01.parquet`. | [Green Taxi Trip Records, January 2025](https://d37ci6vzurychx.cloudfront.net/trip-data/green_tripdata_2025-01.parquet). | 1 178 451 Б. | `84f3a121667157efcbf012c3566a6065df6f8e0312c678cb2f29cd72cc9c0f10`. |
| `taxi_zone_lookup.csv`. | [Taxi Zone Lookup Table](https://d37ci6vzurychx.cloudfront.net/misc/taxi_zone_lookup.csv). | 12 331 Б. | `1a99e105092230f8620f301edcca7f80d3080642ff404d28ed957d3fa222c8ed`. |

## Первичный источник и документация

- [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) - страница публикации файлов, словарей и справочников.
- [Data Dictionary - Green Taxi Trip Records](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_green.pdf) - определения полей.
- [TLC Trip Records User Guide](https://www.nyc.gov/assets/tlc/downloads/pdf/trip_record_user_guide.pdf) - контекст сбора и использования данных.

## Условия использования и важное ограничение

NYC публикует наборы открытых данных без ограничений на использование. Эта папка содержит неизменённые копии файлов NYC TLC; источник, версии, URL и контрольные суммы зафиксированы выше.

Для файлов в этой папке действуют лицензионные условия первоисточника NYC TLC.

## Зафиксированная версия

- Имя исходного файла указывает на январь 2025 года.
- Серверная дата изменения файла при скачивании: 2025-04-23.
- В локальной копии 48 326 строк.
- Фактический диапазон `lpep_pickup_datetime`: от 2024-12-25 23:13:15 до 2025-02-05 18:46:24 (данный пункт является примером ограничения покрытия: обозначение файла не заменяет проверку реальных значений).
