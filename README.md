# Metrostroi Clock Arrive V2.0

**Модель:** Jarrius

**Скрипты:** Alexell

**Website:** https://alexell.ru/

![Metrostroi Clock Arrive](http://mss.community/images/addons/metrostroi_clock_arrive.jpg)

**Оригинальный аддон в Steam Workshop:** https://steamcommunity.com/sharedfiles/filedetails/?id=1975028372

**Описание:**

Мониторы для станций, отображающие линию, направление и время до прибытия состава.

**Как спавнить и сохранять:**

* **Primary (ЛКМ):** Заспавнить монитор / обновить настройки (если наводились на существующий монитор)
* **Secondary (ПКМ):** Удалить монитор
* **Reload (R):** Копировать настройки монитора

При спавне монитора, необходимо указывать в меню спавнера ID станции, номер пути, линию и ее цвет, а также направление (обычно это название следующей станции, но можно указывать и конечную, это на ваш вкус). Обратите внимание, что ID станции и номер пути должны **строго соответствовать данным с платформы на станции**. Вы можете включить галочку Метростроя "Отладочная информация сигнализации", чтобы видеть метки платформы и с них брать значения для часов.

После спавна всех мониторов на карте, необходимо **сохранить** их соответствующей кнопкой меню спавнера. Данные по ним будут сохранены в `data/clocks_arrive.txt` вашего сервера и мониторы будут автоматически спавниться при загрузке карты.

**Будьте внимательны:** нажатие кнопки "Загрузить часы" удалит все заспавненные мониторы на карте, прежде чем загрузить их из файла.

**Исправляем поворот новой модели монитора:**

Если у вас есть сохраненные до обновления аддона мониторы, то скорее всего теперь они повернуты неправильно. Для того чтобы атоматически исправить все мониторы на карте, в спавнере предусмотена кнопка "Исправить старые углы/позиции".

**P.S.** Для того чтобы быстро прописать линию и цвет на все мониторы, используйте кнопку **R** чтобы копировать настройки монитора, затем измените линию и цвет и обновите настройки монитора по **ЛКМ**.

Не забывайте сохранять мониторы после внесения любых изменений!
