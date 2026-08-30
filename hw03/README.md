# ДЗ 3. Строим систему поиска аномалий

Датасет [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) — 284 807 транзакций европейских держателей карт за двое суток. Признаки анонимизированы: `V1`…`V28` — первые 28 главных компонент после PCA, в открытом виде остались только `Time`, `Amount` и метка `Class`. Аномалий 492, то есть 0,17%.

## Просмотр

GitHub иногда не отрисовывает ноутбук целиком, поэтому вот прямые ссылки на nbviewer:

- [Ноутбук](https://nbviewer.org/github/ykornilov/otus_ml_pro/blob/hw03/hw03/anomaly_detection.ipynb)
- [Директория hw03](https://nbviewer.org/github/ykornilov/otus_ml_pro/tree/hw03/hw03/)
- [Запасная ссылка через raw](https://nbviewer.org/url/raw.githubusercontent.com/ykornilov/otus_ml_pro/hw03/hw03/anomaly_detection.ipynb), если nbviewer не поладит с GitHub API

В путях `hw03/hw03` первое — ветка, второе — папка.

## Запуск

```bash
.venv/bin/pip install -r hw03/requirements.txt
```

