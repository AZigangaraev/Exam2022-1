# Вариант 1: Приложение-онлайн магазин
* Приложение загружает список товаров. Запрос: https://raw.githubusercontent.com/AZigangaraev/Exam2022-1/main/var1.json
* Этот список отображается с названием, ценой в виде коллекции (UICollectionView (Flow или Compositional layout)), на одной строчке 2 товара, размеры ячеек одинаковые. Также на каждом item есть кнопка "В корзину (N)", где N — количество уже добавленных объектов в корзину.
* Также есть экран "Корзина". На этом экране показываем все добавленные в корзину товары (они должны кэшироваться с помощью Core Data), с их количеством и стоимостью.
* На экране корзины должна быть возможность удалять товары из корзины.
<img width="1000" alt="ВАРИАНТ 1" src="https://user-images.githubusercontent.com/69074123/212467249-5351a153-2d02-4647-b73e-d9f82c76d863.png">


# Вариант 2: Приложение-менеджер команд
* Приложение загружает список команд с игроками, затем сохраняет локальную копию (использовать для кэширования Core Data). Запрос: https://raw.githubusercontent.com/AZigangaraev/Exam2022-1/main/var2.json
* При переоткрытии, если список игроков до этого был загружен, он не должен заново загружаться.
* Список команд нужно отобразить в виде таблицы (UITableView или UICollectionView).
* В команде должно быть не менее 5 игроков, чтобы команда была "активной". Если игроков в данный момент в команде меньше 5, то команда должна быть помечена, как "неактивная" (отобразить это можно, например, с помощью текста справа в ячейке).
* Можно зайти в детали команды -> нажать на игрока и выбрать новую команду для игрока (из списка команд, который в этот момент должен открыться) и перевести игрока из одной команды в другую, соотвественно, в списке команд (если команда стала неактивной) и на экране самой команды это изменение тоже должно отразиться.
<img width="1000" alt="ВАРИАНТ 2" src="https://user-images.githubusercontent.com/69074123/212467251-ec066c8d-bbe1-453f-95f4-1c5dbc87cdf6.png">

# Критерии оценки:
| Критерий | Оценка |
| ---- | --- |
| Code style | 10 |
| Core Data | 15 |
| Интерфейс (Table/Collection + Navigation + Layout (включая всевозможные Warnings)) | 15 |
| Encoding/decoding + Network | 10 |
