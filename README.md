# 環境構築

```shell
# pyenv-updateをインストール
git clone https://github.com/pyenv/pyenv-update.git $(pyenv root)/plugins/pyenv-update
# pyenv-updateを実行
pyenv update
# pipをアップグレード
pip install -U pip
# pycodestyleをインストール
pip install pycodestyle
# Flake8をインストール
pip install flake8
```

## pip install

```shell
pip install numpy
pip install scipy
pip install pandas
pip install matplotlib
pip install scikit-learn
# pandasが各種データを入出力するためのパッケージ
pip install xlrd
pip install openpyxl
pip install lxml
```
