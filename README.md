# sqlite3-csv

## ダウンロード 
[sqlite-tools-win32-x86-3360000.zip](https://www.sqlite.org/download.html)

▼ createdb.txt
```
create table tbl1(one varchar(10), two smallint);
.quit
```

▼ コマンドプロンプト
```
sqlite3 dbname.sqlite3 < createdb.txt
```
