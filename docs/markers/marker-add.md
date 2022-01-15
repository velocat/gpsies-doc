<!-- markdownlint-disable-next-line first-line-heading -->
### Добавление

1. Перейдите в режим `"Редактирования маркеров"` (F4)  
    ![New Marker](../_media/add-marker-01.jpg)

2. нажмите на карте в точке, где хотите установить новый маркер.
3. В открывшемся "баллуне" укажите название, выберите тип маркера (символ) из списка, и при необходимости добавьте описание.  
  По умолчанию будут установлены значения как указано на картинке:

  ![Image200](../_media/add-marker-02.jpg)

- **Название:** то что будет отображаться в подсказках к маркеру при наведении на него или рядом, если установлено в настройках.
- **Символ:** выбирается из предустановленных в выпадающем списке. Символ отображает тип объекта, для которого устанавливается этот маркер. Подробнее о предустановленых символах и их соответствиям см. раздел [Типы маркеров](#типы-маркеров)
- **Описание:** подробное описание объекта или места.  Используется обычный текст или HTML, например, если необходимо вставить картинку или сделать оформление. Предпочтительно использовать обычный текст, т.к. не все устройства или программы могут правильно воспроизвести HTML.
  Для более корректного ввода HTML форматирования включите режим визуального редактора, уcтановив флажок  
  - [x] **"Оформленный текст"**.
- **Координаты:** устанавливаются автоматически.
- **Высота:** устанавливается автоматичеси и может быть скорректирована вручную.  
  (*примечание: при первоначальной установке маркера высота может быть еще не получена от сервера высот. Для проверки корректности получения высоты можно закрыть баллун маркера и открыть его снова, нажав на значок маркера*).

-----

### Редактирование

1. Перейдите в режим `Редактирования маркеров` (F4)  
2. Для изменения данных маркера, нажмите на него, далее см. [п.3 "Добавление"](#добавление)
3. Для изменения местоположения закройте баллун(если открыт) и переместите маркер в нужную точку на карте.

-----

### Типы маркеров


| символ                        | тип         | &lt;sym&gt; <sup id="a1">[1](#f1)</sup> | соответствие Garmin <sup id="a2">[2](#f2)</sup>
| :---------------------------: | :---------: | :---------: | :------------------------------------------: |
| :fa fa-map-marker-alt fa-fw:  |по умолчанию |Waypoint     | ![waypoint](../_media/symbol/waypoint.png)
| :fa fa-subway fa-fw:          |Станция      |Railway      | ![railway](../_media/symbol/railway.png)
|:fa fa-tram fa-fw:             |Фуникулер    |Funicular    | ![funicular](../_media/symbol/funicular.png)
|:fa fa-utensils fa-fw:         |Еда          |Restaurant   | ![restaurant](../_media/symbol/restaurant.png)
|:fab fa-free-code-camp fa-fw:  |Привал (костёр)|Picnic Area| ![picnic](../_media/symbol/picnic.png)
|:fa fa-grip-lines fa-fw:       |Мост         |Bridge       | ![bridge](../_media/symbol/bridge.png)
|:fa fa-water fa-fw:            |Брод         |brod         | -
|:fa fa-dungeon fa-fw:          |Пещера       |cave         | -
|:fa fa-times fa-fw:            |Перевал      |Crossing     | ![crossing](../_media/symbol/crossing.png)
|:fa fa-mountain fa-fw:         |Вершина, гора|Summit       | ![summit](../_media/symbol/summit.png)
|:fa fa-times fa-fw:            |Пересечение  |Crossing     | ![crossing](../_media/symbol/crossing.png)
|:fa fa-campground fa-fw:       |Кемпинг      |Campground   | ![camping](../_media/symbol/camping.png)
|:fa fa-caravan fa-fw:          |Автокемпинг  |RV Park      | ![rv park](../_media/symbol/rv-park.png)
|:fa fa-bed fa-fw:              |Отель        |Lodging      | ![lodging](../_media/symbol/lodging.png)
|:fa fa-tint fa-fw:             |Питьевая вода|Drinking Water| ![drinking water](../_media/symbol/drinkin.png)
|:fa fa-shower fa-fw:           |Душ          |Shower       | ![shower](../_media/symbol/shower.png)
|:fa fa-plug fa-fw:             |Электричество|plug         | -
|:fa fa-home fa-fw:             |Дом, жильё   |Residence    | ![residence](../_media/symbol/recidence.png)
|:fab fa-fort-awesome fa-fw:    |Достопримечательность|sight| -
|:fa fa-monument fa-fw:         |Монумент, памятник|monument| -
|:fa fa-landmark fa-fw:         |Музей        |Museum       | ![museum](../_media/symbol/museum.png)
|:fa fa-info-circle fa-fw:      |Информация   |Information  | ![information](../_media/symbol/info.png)
|:fa fa-exclamation-triangle fa-fw:|Внимание! |attention    | -
|:fa fa-skull-crossbones fa-fw: |Опасность    |Skull and Crossbones| ![danger](../_media/symbol/skull.png)
|:fa fa-lightbulb fa-fw:        |Идея         |Light        | ![light](../_media/symbol/light.png)
|:fa fa-star fa-fw:             |Звезда       |generic      | -
|:fa fa-heart fa-fw:            |Избранное    |Favorite     | ![favorite](../_media/symbol/favorite.png)
|:fas fa-tree fa-fw:            |Парк, лес    |Park         | ![park](../_media/symbol/park.png)
|:fa fa-umbrella-beach fa-fw:   |Пляж         |Beach        | ![beach](../_media/symbol/beach.png)
|:fa fa-swimmer fa-fw:          |Место для купания|Swimming Area| ![swimming](../_media/symbol/swimming.png)
|:fa fa-restroom fa-fw:         |Туалет       |Restroom     | ![restroom](../_media/symbol/restroom.png)
|                               |Геокешинг    |Geocache     | ![geocashing](../_media/symbol/geocash.png)
|:fa fa-ambulance fa-fw:        |Медицинская помощь|Medical Facility| ![medical](../_media/symbol/medical.png)
|:fa fa-compress-arrows-alt fa-fw:|Место встречи|meeting    | -
|:fa fa-map-signs fa-fw:        |Указатель    |plate        | -
|:fa fa-arrow-left fa-fw:       |Налево       |left         | -
|:fa fa-arrow-right fa-fw:      |Направо      |right        | -
|:fa fa-undo fa-fw:             |Назад        |TracBack Point| ![trackback](../_media/symbol/trackback.png)
|:fa fa-ban fa-fw:              |Стоп         |Stop         | ![stop](../_media/symbol/stop.png)
|:fa fa-flag fa-fw:             |Флаг         |Flag         | ![flag](../_media/symbol/flag.png)
|:fa fa-flag-checkered fa-fw:   |Финиш        |finish       | -
|:fa fa-eye fa-fw:              |Обзор        |Flag, Red    | ![flag red](../_media/symbol/flag-red.png)
|:fa fa-camera-retro fa-fw:     |Фото         |Scenic Area  | ![scenic](../_media/symbol/scenic.png)
|:fa fa-shield-alt fa-fw:       |Полиция      |Police Station| ![police](../_media/symbol/police.png)
|:fa fa-passport fa-fw:         |Пасспортный контроль|passport| -
|:fa fa-church fa-fw:           |Церковь      |Church       | ![church](../_media/symbol/church.png)
|:fa fa-mosque fa-fw:           |Мечеть       |mosque       | -
|:fa fa-dollar-sign fa-fw:      |Банк         |Bank         | ![bank](../_media/symbol/bank.png)
|:fa fa-hand-holding-usd fa-fw: |Банкомат     |cash         | -
|:fa fa-plane fa-fw:            |Аэропорт     |Airport      | ![airport](../_media/symbol/airport.png)
|:fa fa-anchor fa-fw:           |Причал       |Anchor       | ![ancor](../_media/symbol/anchor.png)
|:fa fa-futbol fa-fw:           |Стадион      |Stadium      | ![stadium](../_media/symbol/stadium.png)
|:fa fa-cart-plus fa-fw:        |Магазин      |Shopping Center| ![shop](../_media/symbol/shop.png)
|:fa fa-prescription fa-fw:     |Аптека       |Pharmacy     | ![pharmacy](../_media/symbol/pharmacy.png)
|:fa fa-clinic-medical fa-fw:   |Больница     |Hospital, Euro| ![hospital](../_media/symbol/hospital.png)
|:fa fa-tools fa-fw:            |Сервис, ремонт|service     | -
|:fa fa-trash-alt fa-fw:        |Мусор        |trash        | -
|:fa fa-bacon fa-fw:            |Водопад      |waterfall    | -
|:fa fa-fish fa-fw:             |Рыбылка      |Fishing Area | ![fishing](../_media/symbol/fishing.png)
|:fa fa-biking fa-fw:           |Велодорожка  |Bike Trail   | ![bike](../_media/symbol/bike.png)
|:fa fa-parking fa-fw:          |Парковка     |Parking Area | ![parking](../_media/symbol/parking.png)

<b id="f1"> [1] </b> *&lt;sym&gt; - значение тега точки трека (wpt), который используется другими программами и устройствами для отображения соответствующего символа.* [↩](#a1)  
<b id="f2"> [2] </b> *Соответствие названия символа &lt;sym&gt; изображениям, использумыми Garmin. [Полная таблица символов](/markers/garmin.md)  
    В трех ячейках указаны соответствующие символы для: mapsource, gpsmap и 24х24 (basecamp).* [↩](#a2)

*примечание: в случае использования значка не имеющего соответствия программе/прибору, поле sym будет проигнорировано и значок точки будет отображен как установлено в программе/приборе по-умолчанию. Например, для устройств Garmin это будет "Waypoint"*
