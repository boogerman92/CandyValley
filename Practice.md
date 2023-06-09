# Практическая часть:
## a Все найденные мною баги офрмленны в Issues
## b После крупного обновления в четверг массово поступают жалобы от техподдержки, что упала производительность android-версии игры. В пятницу утром менеджер заводит задачу на выяснение проблемы и ставит ее на вас.
### 1) Сбор информации: Получить более подробное описание проблемы; Узнать какие конкретно аспекты игры замедлились.
### 2) Воспроизведение проблемы: Попробовать воспроизвести проблему на локальном устройстве, используя android-версию игры после обновления; Замерить и сравнить производительность с предыдущей версией игры или с более ранними обновлениями.
### 3) Профилирование производительности: Использовать инструменты профилирования, такие как Android Profiler, для анализа производительности приложения; Идентифицировать узкие места, процессы, потребление ресурсов или задержки, которые могут вызывать снижение производительности.
### 4) Коммуникация с программистами: Сообщить программистам о результатах исследования и профилирования производительности.
### 5) Приоритезация и исправление: Совместно с программистами определить наиболее критические проблемы, которые снижают производительность, и установить приоритеты.
## c Чек-лист и тест-кейсы на проверку нового игрового эпизода:
### 1 Чек-лист:
#### Проверка основного сюжета:
##### Проверить, что основной в новом эпизоде продолжается сбор трёх предметов для прохождения эпизода.
#### Проверка новых механик игры:
##### Протестировать все новые игровые механики, введенные в новом эпизоде, и убедиться, что они работают корректно.
##### Проверить взаимодействие новых механик с существующими элементами игры.
#### Тестирование игровых уровней:
##### Пройти каждый уровень нового эпизода, убедиться, что они доступны и проходимы в правильной последовательности.
### 2 Тест-кейсы:
#### Прохождение первого уровня нового эпизода:
##### 1)Вход в игру.
##### 2)Выбор нового эпизода.
##### 3)Запуск первого уровня.
##### 4)Прохождение уровня в соответствии с заданными правилами и условиями.
##### 5)Проверка окончания уровня и перехода к следующему.
#### Проверка новой игровой механики:
##### 1)Загрузка игры.
##### 2)Переход к уровню, где используется новая игровая механика.
##### 3)Тестирование функциональности и правильности работы новой механики.
##### 4)Убедиться, что новая механика не нарушает общий игровой процесс и взаимодействует с другими элементами игры.
