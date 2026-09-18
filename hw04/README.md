# ДЗ 4. Симуляция распространения болезни. Работа с NetworkX

Датасет [US Flights Data 2008](https://www.kaggle.com/datasets/vikalpdongre/us-flights-data-2008) — внутренние рейсы США по данным Министерства транспорта. В работе взят январь: 587 130 рейсов между 286 аэропортами за 31 сутки.

Инфекция распространяется по SI-модели: аэропорт бывает здоровым или заражённым, вылечиться нельзя, а здоровый заражается с вероятностью `p`, если к нему прилетает самолёт из заражённого города. Стартовый аэропорт — Allentown (`ABE`).

## Просмотр

GitHub иногда не отрисовывает ноутбук целиком, поэтому вот прямые ссылки на nbviewer:

- [Ноутбук](https://nbviewer.org/github/ykornilov/otus_ml_pro/blob/hw04/hw04/disease_spread.ipynb)
- [Директория hw04](https://nbviewer.org/github/ykornilov/otus_ml_pro/tree/hw04/hw04/)
- [Запасная ссылка через raw](https://nbviewer.org/url/raw.githubusercontent.com/ykornilov/otus_ml_pro/hw04/hw04/disease_spread.ipynb), если nbviewer не поладит с GitHub API

В путях `hw04/hw04` первое — ветка, второе — папка.

## Запуск

```bash
.venv/bin/pip install -r hw04/requirements.txt
```

