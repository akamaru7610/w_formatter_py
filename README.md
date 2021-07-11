# w_formatter_py

## tool
- [black](https://github.com/psf/black)
- [autoflake](https://pypi.org/project/autoflake/)
- [pre-commit](https://pre-commit.com/)
- [mypy](https://github.com/python/mypy)
- [isort](https://pypi.org/project/isort/)

## install
```
pip install black
pip install autoflake
pip install pre-commit
pip install mypy
pip install isort
```
## use
```
autoflake --in-place --remove-unused-variables example.py
```

## quickstart
black->autoflake->mypy->isort->pre-commit

## etc

## ref
- [もうPythonの細かい書き方で議論しない。blackで自動フォーマットしよう](https://blog.hirokiky.org/entry/2019/06/03/202745)
- [Python の静的型、すごい mypy!](https://qiita.com/t2y/items/2a1310608da7b5c4860b)
