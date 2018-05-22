# Intro-Data-Science
『ビジネス活用事例で学ぶ データサイエンス入門』のコードをPython3に書き換えたもの  
URL: http://www.sbcr.jp/products/4797376333.html

### 使い方
-  githubからclone  
```
git clone https://github.com/hashk1/Intro-Data-Science.git
```
- 以下のサイトからデータをダウンロード  
http://download.sbcr.jp/getDLService.php?id=e55bf123ceae6c99935d644424d9eb39
```
wget http://download.sbcr.jp/getDLService.php?id=e55bf123ceae6c99935d644424d9eb39 -O DL76333.zip
```
- ファイルを展開し、中身をREADME.mdと同じディレクトリに配置
```
unzip DL76333.zip
cd DL76333
mv * ../
```
- Rフォルダの名前をDataに書き換える
```
cd ../
mv R Data
rmdir DL76333
```
- Pythonフォルダに移動してJupyter Notebookを立ち上げる  
```
cd Python
jupyter notebook
```
- Jupyter Notebookが立ち上がったら各チャプターごとの.ipynbファイルを実行
