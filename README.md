# hw_python_oop (Money and calories calculator)
Калькулятор денег и калорий - инструменты для контроля расходов и доходов

Условия задачи

Создайте два калькулятора: для подсчёта денег и калорий. Нужна только логика — отдельный класс для каждого из калькуляторов.

Калькулятор денег должен уметь:
- Сохранять новую запись о расходах методом add_record()
- Считать, сколько денег потрачено сегодня методом get_today_stats()
- Определять, сколько ещё денег можно потратить сегодня в рублях, долларах или евро — метод get_today_cash_remained(currency)
- Считать, сколько денег потрачено за последние 7 дней — метод get_week_stats()

Калькулятор калорий должен уметь:
- Сохранять новую запись о приёме пищи— метод add_record()
- Считать, сколько калорий уже съедено сегодня — метод get_today_stats()
- Определять, сколько ещё калорий можно/нужно получить сегодня — метод get_calories_remained()
- Считать, сколько калорий получено за последние 7 дней — метод get_week_stats()

Общая функциональность калькуляторов (долна быть заложена в класс Calculator):
- Они должны уметь хранить какие-то записи (о еде или деньгах, но по сути - всё числа и даты) 
- Знать дневной лимит (сколько в день можно истратить денег или сколько калорий можно получить)
- Суммировать записи за конкретные даты

Конструктор класса Calculator должен принимать один аргумент: 
— число limit (дневной лимит трат/калорий, который задал пользователь). 
