<!-- markdownlint-disable-next-line first-line-heading -->
### Добавление

1. Перейдите в режим `"Редактирования маркеров"` (F4)  

   ![New Marker](../_media/add-marker-01.jpg)

2. Нажмите на карте в точке, где хотите установить новый маркер
3. В открывшемся "баллуне" укажите название, выберите тип маркера (символ) из списка, и при необходимости добавьте описание.  
  По умолчанию будут установлены значения как указано на картинке:

  | |
  | :---: |
  |![Image200](../_media/add-marker-02.jpg)

- **Название:** то что будет отображаться в подсказках к маркеру при наведении на него или рядом, если установлено в настройках.
- **Символ:** выбирается из предустановленных в выпадающем списке. Символ отображает тип объекта, для которого устанавливается этот маркер. Подробнее о предустановленых символах и их соответствиям см. раздел [Типы маркеров](markers/marker-add.md?id=Типы-маркеров)
- **Описание:** подробное описание объекта или места.  Используется обычный текст или HTML, например, если необходимо вставить картинку или сделать оформление. Предпочтительно использовать обычный текст, т.к. не все устройства или программы могут правильно воспроизвести HTML.
  Для более корректного ввода HTML форматирования включите режим визуального редактора, уcтановив флажок  
  - [x] **"Оформленный текст"**.
- **Координаты:** устанавливаются автоматически.
- **Высота:** устанавливается автоматичеси и может быть скорректирована вручную.  
  
>[!NOTE]
>*При первоначальной установке маркера высота может быть еще не получена от сервера высот.  
>Для проверки корректности получения высоты можно закрыть баллун маркера и открыть его снова, нажав на значок маркера*.

-----

### Редактирование

1. Перейдите в режим `Редактирования маркеров` (F4)  
2. Для изменения данных маркера, нажмите на него, далее см. ["Добавление" п.3](markers/marker-add.md?id=Добавление)
3. Для изменения местоположения закройте баллун(если открыт) и переместите маркер в нужную точку на карте.

-----

### Типы маркеров


| символ                        | тип         | &lt;sym&gt; <sup id="a1">[1](#f1)</sup> | соответствие Garmin <sup id="a2">[2](#f2)</sup>
| :---------------------------: | :---------: | :---------: | :------------------------------------------: |
| :fa fa-map-marker-alt fa-fw fa-lg:  |по умолчанию |Waypoint     | ![waypoint](../_media/symbol/waypoint.png)
| :fa fa-subway fa-fw fa-lg:          |Станция      |Railway      | ![railway](../_media/symbol/railway.png)
|:fa fa-tram fa-fw fa-lg:             |Фуникулер    |Funicular    | ![funicular](../_media/symbol/funicular.png)
|:fa fa-utensils fa-fw fa-lg:         |Еда          |Restaurant   | ![restaurant](../_media/symbol/restaurant.png)
|:fab fa-free-code-camp fa-fw fa-lg:  |Привал (костёр)|Picnic Area| ![picnic](../_media/symbol/picnic.png)
|:fa fa-grip-lines fa-fw fa-lg:       |Мост         |Bridge       | ![bridge](../_media/symbol/bridge.png)
|:fa fa-water fa-fw fa-lg:            |Брод         |brod         | -
|:fa fa-dungeon fa-fw fa-lg:          |Пещера       |cave         | -
|:fa fa-times fa-fw fa-lg:            |Перевал      |Crossing     | ![crossing](../_media/symbol/crossing.png)
|:fa fa-mountain fa-fw fa-lg:         |Вершина, гора|Summit       | ![summit](../_media/symbol/summit.png)
|:fa fa-times fa-fw fa-lg:            |Пересечение  |Crossing     | ![crossing](../_media/symbol/crossing.png)
|:fa fa-campground fa-fw fa-lg:       |Кемпинг      |Campground   | ![camping](../_media/symbol/camping.png)
|:fa fa-caravan fa-fw fa-lg:          |Автокемпинг  |RV Park      | ![rv park](../_media/symbol/rv-park.png)
|:fa fa-bed fa-fw fa-lg:              |Отель        |Lodging      | ![lodging](../_media/symbol/lodging.png)
|:fa fa-tint fa-fw fa-lg:             |Питьевая вода|Drinking Water| ![drinking water](../_media/symbol/drinkin.png)
|:fa fa-shower fa-fw fa-lg:           |Душ          |Shower       | ![shower](../_media/symbol/shower.png)
|:fa fa-plug fa-fw fa-lg:             |Электричество|plug         | -
|:fa fa-home fa-fw fa-lg:             |Дом, жильё   |Residence    | ![residence](../_media/symbol/recidence.png)
|:fab fa-fort-awesome fa-fw fa-lg:    |Достопримечательность|sight| -
|:fa fa-monument fa-fw fa-lg:         |Монумент, памятник|monument| -
|:fa fa-landmark fa-fw fa-lg:         |Музей        |Museum       | ![museum](../_media/symbol/museum.png)
|:fa fa-info-circle fa-fw fa-lg:      |Информация   |Information  | ![information](../_media/symbol/info.png)
|:fa fa-exclamation-triangle fa-fw fa-lg:|Внимание! |attention    | -
|:fa fa-skull-crossbones fa-fw fa-lg: |Опасность    |Skull and Crossbones| ![danger](../_media/symbol/skull.png)
|:fa fa-lightbulb fa-fw fa-lg:        |Идея         |Light        | ![light](../_media/symbol/light.png)
|:fa fa-star fa-fw fa-lg:             |Звезда       |generic      | -
|:fa fa-heart fa-fw fa-lg:            |Избранное    |Favorite     | ![favorite](../_media/symbol/favorite.png)
|:fas fa-tree fa-fw fa-lg:            |Парк, лес    |Park         | ![park](../_media/symbol/park.png)
|:fa fa-umbrella-beach fa-fw fa-lg:   |Пляж         |Beach        | ![beach](../_media/symbol/beach.png)
|:fa fa-swimmer fa-fw fa-lg:          |Место для купания|Swimming Area| ![swimming](../_media/symbol/swimming.png)
|:fa fa-restroom fa-fw fa-lg:         |Туалет       |Restroom     | ![restroom](../_media/symbol/restroom.png)
|                               |Геокешинг    |Geocache     | ![geocashing](../_media/symbol/geocash.png)
|:fa fa-ambulance fa-fw fa-lg:        |Медицинская помощь|Medical Facility| ![medical](../_media/symbol/medical.png)
|:fa fa-compress-arrows-alt fa-fw fa-lg:|Место встречи|meeting    | -
|:fa fa-map-signs fa-fw fa-lg:        |Указатель    |plate        | -
|:fa fa-arrow-left fa-fw fa-lg:       |Налево       |left         | -
|:fa fa-arrow-right fa-fw fa-lg:      |Направо      |right        | -
|:fa fa-undo fa-fw fa-lg:             |Назад        |TracBack Point| ![trackback](../_media/symbol/trackback.png)
|:fa fa-ban fa-fw fa-lg:              |Стоп         |Stop         | ![stop](../_media/symbol/stop.png)
|:fa fa-flag fa-fw fa-lg:             |Флаг         |Flag         | ![flag](../_media/symbol/flag.png)
|:fa fa-flag-checkered fa-fw fa-lg:   |Финиш        |finish       | -
|:fa fa-eye fa-fw fa-lg:              |Обзор        |Flag, Red    | ![flag red](../_media/symbol/flag-red.png)
|:fa fa-camera-retro fa-fw fa-lg:     |Фото         |Scenic Area  | ![scenic](../_media/symbol/scenic.png)
|:fa fa-shield-alt fa-fw fa-lg:       |Полиция      |Police Station| ![police](../_media/symbol/police.png)
|:fa fa-passport fa-fw fa-lg:         |Пасспортный контроль|passport| -
|:fa fa-church fa-fw fa-lg:           |Церковь      |Church       | ![church](../_media/symbol/church.png)
|:fa fa-mosque fa-fw fa-lg:           |Мечеть       |mosque       | -
|:fa fa-dollar-sign fa-fw fa-lg:      |Банк         |Bank         | ![bank](../_media/symbol/bank.png)
|:fa fa-hand-holding-usd fa-fw fa-lg: |Банкомат     |cash         | -
|:fa fa-plane fa-fw fa-lg:            |Аэропорт     |Airport      | ![airport](../_media/symbol/airport.png)
|:fa fa-anchor fa-fw fa-lg:           |Причал       |Anchor       | ![ancor](../_media/symbol/anchor.png)
|:fa fa-futbol fa-fw fa-lg:           |Стадион      |Stadium      | ![stadium](../_media/symbol/stadium.png)
|:fa fa-cart-plus fa-fw fa-lg:        |Магазин      |Shopping Center| ![shop](../_media/symbol/shop.png)
|:fa fa-prescription fa-fw fa-lg:     |Аптека       |Pharmacy     | ![pharmacy](../_media/symbol/pharmacy.png)
|:fa fa-clinic-medical fa-fw fa-lg:   |Больница     |Hospital, Euro| ![hospital](../_media/symbol/hospital.png)
|:fa fa-tools fa-fw fa-lg:            |Сервис, ремонт|service     | -
|:fa fa-trash-alt fa-fw fa-lg:        |Мусор        |trash        | -
|:fa fa-bacon fa-fw fa-lg:            |Водопад      |waterfall    | -
|:fa fa-fish fa-fw fa-lg:             |Рыбылка      |Fishing Area | ![fishing](../_media/symbol/fishing.png)
|:fa fa-biking fa-fw fa-lg:           |Велодорожка  |Bike Trail   | ![bike](../_media/symbol/bike.png)
|:fa fa-parking fa-fw fa-lg:          |Парковка     |Parking Area | ![parking](../_media/symbol/parking.png)

<b id="f1"> [1] </b> *&lt;sym&gt; - значение тега точки трека (wpt), который используется другими программами и устройствами для отображения соответствующего символа.* [↩](#a1)  
<b id="f2"> [2] </b> *Соответствие названия символа &lt;sym&gt; изображениям, использумыми Garmin. [Полная таблица символов](/markers/garmin.md)  
    В трех ячейках указаны соответствующие символы для: mapsource, gpsmap и 24х24 (basecamp).* [↩](#a2)

>[!NOTE]
>В случае использования значка не имеющего "соответствия" программе/прибору, поле `sym` будет проигнорировано и значок точки будет отображен как установлено в программе/приборе по-умолчанию. Например, для устройств Garmin это будет `Waypoint`
