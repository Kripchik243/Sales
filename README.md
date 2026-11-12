# Sales
  Учебный анализ синтетического набора из 250 продаж. Данные не являются реальными продажами.
# Запуск
  ```bash
git clone https://github.com/Kripchik243/Sales.git
cd Sales
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```
В Jupyter открой `sales.ipynb` и выбери **Kernel → Restart Kernel and Run All Cells**, чтобы выполнить все ячейки по порядку.

# Что будет оцениваться
  1. Наиболее продаваемый товар: Веб-камера 90, сумма 'quantity' по 'product'
  2. Город с большей выручкой: Казань 2519000, сумма 'revenue_rub' по 'region'
  3. Чаще всего используемый магазин: Интернет-магазин 98, подсчёт строк по 'sales_channel'
  4. Наибольший средний чек среди городов: Санкт-Петербург 52152.173913, среднее значение 'revenue_rub' (без учёта скидки) по 'region'
       
