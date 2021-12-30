---
template: support.html
hide:
  - navigation
  - toc
  - feedback
---

# Помочь

### Нашли ошибку?

Работа по такому описанию очень трудозатратна, кроме того, надо поддерживать репозиторий в актуальном состоянии. Поэтому в первую очередь на человеческий язык будут переводиться самые важные стандарты.

[Пожаловаться или предложить идею](https://github.com/zeegin/v8std-for-humans/issues/new){ .md-button }

### Хотите внести исправление?

Можно просто нажать на иконку `Редактировать` и прислать Pull Request.

Хотите изменить дизайн, посмотреть как будет выглядеть правка локально?
Выполните следующие операции на своем компьютере:

```cmd
pip install --upgrade pip
pip install mkdocs mkdocs-material mkdocs-minify-plugin mkdocs-redirects pygments-bsl

git clone https://github.com/zeegin/v8std-for-humans.git

cd v8std-for-humans

mkdocs serve --watch-theme
```

Теперь по адресу `http://127.0.0.1:8000` можно открыть документацию на своем компьютере.
