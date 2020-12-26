# poetry で自作Pythonライブラリ作成

ライブラリを作成・テスト実行・ユニットテスト実行・テストのためのローカルインストールまでを試す

[poetry](https://github.com/python-poetry/poetry) を試す

https://qiita.com/moisutsu/items/0393de9a248a937a85ad


[公式ページ](https://cocoatomo.github.io/poetry-ja/cli/)

[Poetryを使ったPythonパッケージ開発からPyPI公開まで - PYTHONIC BOOM BOOM HEAD](https://kk6.hateblo.jp/entry/2018/12/20/124151)


## install

[公式ページ](https://cocoatomo.github.io/poetry-ja/cli/)

```
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
```




## パッケージ作成

```
~/gitwork/learn_poetry
[pharaohkj]$ poetry new my-python-lib
Created package my_python_lib in my-python-lib
```


テストの実行

~/gitwork/package-name/project-name
[pharaohkj]$ pwd

/Users/pharaohkj/gitwork/package-name/project-name
~/gitwork/package-name/project-name

[pharaohkj]$ pytest
=== test session starts ===
platform darwin -- Python 3.8.5, pytest-6.1.1, py-1.9.0, pluggy-0.13.1
rootdir: /Users/pharaohkj/Dropbox/osx/gitwork/package-name/project-name
collected 1 item

tests/test_project_name.py .                                                                                                                        [100%]

=== 1 passed in 0.02s ===
