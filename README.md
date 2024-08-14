# 生協IoT班 アンケート結果分析
アンケート結果の分析に用いたコードを共有します。\
念のため、コードの出力部分は削除した状態でコミットしています。整形後のデータは、Notionに貼り付けているGoogle Driveから確認してください。

## 自身の環境でコードを実行する際は
仮想環境を構築してから実行することをお勧めします。なお、以下の例は、Windowsマシンで、かつIDEとしてVSCodeを利用している場合のものなので、他の環境を利用している場合はご注意ください。

仮想環境は以下のコマンドで構築できます。`environment_name`の部分を任意の名前に変更して実行してください。
```
python3 -m venv environment_name
```
処理が終わったら、以下のコマンドで仮想環境をアクティベートします。
```
environment_name/scripts/activate.ps1
```
正常にアクティベートされると、ターミナルに表示されているカレントディレクトリの先頭部分に、仮想環境の名前が表示されるので確認してください。

正常にアクティベートされていることが確認出来たら、必要なライブラリを`requirements.txt`で一括インストールします。以下のコマンドを実行してください。
```
pip install -r requirements.txt
```
これで仮想環境の準備は終了です。

## Tips
### 仮想環境をディアクティベートしたい
以下のコマンドを実行してください。
```
deactivate
```

### 仮想環境を削除したい
`environment_name`のフォルダを削除してください。

