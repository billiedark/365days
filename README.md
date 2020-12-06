<h1 align="center">
  <br>
  <a href="https://t.me/baccaraaa"><img src="https://www.python.org/static/opengraph-icon-200x200.png" alt="Python"></a>
  <br>
  Python
  <br>
</h1>

<h4 align="center">Получение даты от 0 до 365</h4>


## math model
- Получаем дату 1 января текущего года
- Получаем дату текущего дня
- Отнимает первую полученную дату и вторую, получаем разность дней, это и будет днем от 0 до 365.

## code
```python
date_NOW = datetime.date.today()
date_START_YEAR = datetime.date(year = t.year, month = 1, day = 1)
date_NOW365 = (date_NOW - date_START_YEAR).days # 348
```
