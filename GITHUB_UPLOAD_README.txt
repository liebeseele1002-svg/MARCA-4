MARCA-4 GitHub Pages root-flat版

今回の原因:
GitHub上では画像がリポジトリ直下にアップロードされています。
そのため index.html が assets/images/... を見に行くと画像が表示されません。
この版では画像をすべてリポジトリ直下のファイル名で参照するように作り直しました。

アップロード方法:
1. ZIPを解凍
2. 中身をすべて MARCA-4 リポジトリへアップロード
3. 必ず既存の index.html を上書き
4. Commit changes を押す

アップロードする主な中身:
index.html
main-visual.jpg
marca-mark.png
vending-machine.jpg
about-image.jpg
health-exercise-band.jpg
outdoor-tent.jpg
pet-water-bottle.jpg
404.html
thanks.html
robots.txt
sitemap.xml
.nojekyll

assetsフォルダは使わない構成です。
