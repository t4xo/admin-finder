# Breacher
A script to find admin login pages and EAR vulnerabilites.

#### İşlevleri
- [x] İşlevsel Programımız
- [x] Büyük Wordlistimiz (482 adet)
- [x] Php, asp ve html Destekler
- [x] Potansiyel EAR açıklarını tarar
- [x] Robots.txt dosyalarını tarar

### Kullanım
Php Dilinde Siteler İçin
python adminfinder.py -u example.com --type php
```
- Check all paths with php extension with threads
```
python breacher -u example.com --type php --fast
```
- Check all paths without threads
```
python breacher -u example.com
```
- Adding a custom path. For example if you want all paths to start with /data (example.com/data/...) you can do this:
```
python breacher -u example.com --path /data
```
<b>Note: </b> When you specify an extension using <b>--type</b> option, Breacher includes paths of that extension as well as paths with no extensions like <b>/admin/login</b>

#### Video Demo

[![Breacher](https://i.imgur.com/D9my9A5.png)](https://youtu.be/BEpt5JmcWPk)
