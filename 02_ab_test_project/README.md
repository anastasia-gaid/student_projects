# Анализ пользовательского поведения в мобильном приложении. Анализ результатов А/А/В теста.
## Цель проекта: 
Подготовить анализ воронки продаж мобильного приложения стартапа по продаже продуктов питания. Провести анализ результатов A/A/B-тестирования по изменению шрифтов в приложении с двумя контрольными группами со старыми шрифтами и одной экспериментальной — с новыми.

## Описание данных:

Таблица `/datasets/logs_exp.csv`.
Каждая запись в логе — это действие пользователя, или событие.

* `EventName` — название события;
* `DeviceIDHash` — уникальный идентификатор пользователя;
* `EventTimestamp` — время события;
* `ExpId` — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Вывод:

По результатам анализа A/A/B-эксперимента следует:

Ни для одного события в приложении, не найдены статистически значимые различия в долях пользователей между экспериментальной группой 247 и тремя контрольными группами 246, 247 и объединённой контрольной группой 249.

Следовательно, изменение шрифта приложения не изменяет конверсию ни на одном из последовательных событий в цепочке приложения, ни в сторону увеличения, ни в сторону уменьшения.
