<!-- markdownlint-disable-next-line first-line-heading -->
- Перейдите в режим автоматической маршрутизации  

  ![route](../_media/routing-icon.jpg)

- Выберите сервис маршрутизации

  ![Image200](../_media/routing-btn.jpg)

  >Варианты:
  >
  > - `Graphhooper`: доступен для всех до исчерпания бесплатной дневной квоты или при наличии собственного API-ключа 
  > - `OpenRouteService`: доступен только при наличии собственного API-ключа

  Как подключить собственные ключи, а также о бесплатных дневных квотах, см. в разделе [API-keys](../api-keys.md)

- Выберите тип маршрутизации  
  От этого зависит, как сервис будет прокладывать маршрут, например, выбрав "автомобиль", сервис будет игнорировать тропинки и прочее, недоступное для этого вида транспорта.

- Если у Вас еще нет точек трека, установите на карте начальную точку маршрута ![green-marker](../_media/google-maps-green.png)(зеленый маркер),  
  если на карте уже есть точки трека, маршрут начнет прокладываться от последней точки активного сегмента.

- Установите на карте финишную точку маршрута ![red-marker](../_media/google-maps-pin.png) (красный маркер).  
  Маршрут построится автоматически.

  ![Image400](../_media/routing-trk.jpg)

- Финишную точку (красный маркер) можно перемещать по карте, тем самым подыскивая наиболее приемлимый для Вас маршрут.  
  С каждым перемещением будет прокладываться новый маршрут.

- Если финишная точка установлена там, где нет дорог, например в лесу, маршрутизатор обозначит путь к этой точке серой линией от ближайшей доступной для прокладки маршрута точки. Трек будет построен до этой точки.  
  Если Вам всё же необходимо построить трек до этой "недоступной" точки, необходимо перейти в ручной режим редактирования и проложить этот путь самостоятельно.

- Чтобы выйти из режима автоматической прокладки маршрута, нажмите кнопку `Закончить`

>[!NOTE]
> Чтобы проложить маршрут внутри участка уже имеющегося трека, ознакомьтесь с разделом [Фрагменты - автопрокладка маршрута](../tracks/track-segments?id=Действия-с-Фрагментом)