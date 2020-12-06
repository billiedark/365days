<h4 align="center">Получение даты от 0 до 365</h4>
<h1 align="center">
  Python
</h1>

## math model
- Получаем дату 1 января текущего года
- Получаем дату текущего дня
- Отнимает первую полученную дату и вторую, получаем разность дней, это и будет днем от 0 до 365.

## code
date_NOW = datetime.date.today()
date_START_YEAR = datetime.date(year = t.year, month = 1, day = 1)
date_NOW365 = (date_NOW - date_START_YEAR).days # 348
