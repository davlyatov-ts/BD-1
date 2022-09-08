# Задача №1

Архитектор ПО решил проконсультироваться у вас, какой тип БД лучше выбрать для хранения определенных данных.<br>

Он вам предоставил следующие типы сущностей, которые нужно будет хранить в БД:<br>

```
Электронные чеки в json виде
Склады и автомобильные дороги для логистической компании
Генеалогические деревья
Кэш идентификаторов клиентов с ограниченным временем жизни для движка аутенфикации
Отношения клиент-покупка для интернет-магазина
```

## Ответ

1. **MongoDB** - документно-ориентирвоанные СУБД в отличие от хранилищ типа ключ-значение, выборка по запросу к документному хранилищуможет содержать части большого  количества документов без полной загрузки этих документов в оперативную память<br>

2. **Amazon Neptune** - графовые СУБД для задач с естественной графовой структурой данных графовые СУБД могут существенно превосходитьреляционные по производительности, а также иметь преимущества в наглядности представления и простоте внесения изменений в схему базы данных<br>

3. **System 2000** - Иерархическая СУБД представляет собой связный неориентированный граф древовидной структуры.<br>

4. **Redis**/Memcached - СУБД «ключ-значение» обрабатывают данные как одну непрозрачную коллекцию, которая может иметь разные поля длякаждой записи. Это обеспечивает значительную гибкость и более точно следует современным концепциям, таким как объектно-ориентированноепрограммирование<br>

5.  Документо-ориентированные СУБД.<br>
