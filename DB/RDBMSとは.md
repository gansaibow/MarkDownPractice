#リレーショナルデータベースとは

RDBMS(Relational DataBase Management System)

## Database = データベース
### 起源
 第二次大戦後の米軍が、膨大な資料を効率的に管理することを目的として、情報を一つの基地に集めた。この集められた情報の基地をデータベース(Database)と読んだのが始まり  
現在では、  
 データベースは何らかの規則を持ったデータの集まりを意味する。  
 データに対する管理のための機能をまとめてデータベースという。  
 情報を活用する機能がついて初めて「データベース」と呼べる。  

### データベースの構成  
- **レコード** = １件のデータ   
- **カラム** = 項目
- **テーブル** = レコードの集まりである表

### Relation = 関係
「それぞれ関係を持った」複数のテーブルから、必要なテーブルから必要な部分だけを集めて利用する  


### 特徴
Excel = 文字列でも数値でもどこにでもデータ入力が出来る。  
DB = Aというカラムは整数しか入れられないと決めたら、Aカラムには文字列は入れられない。  
１度行った操作を元に戻すには「トランザクション」などの機能を使わなくてはならない。

### 有名なRDBMS
- Oracle : 商用RDBMSとして、世界で最も多く使われている。
- Access : Microsoft社のOfficeファミリーのRDBMS
- Microsoft SQL Server : Microsoft社の商用RDBMS
- PostgresSQL : オープンソースのRDBMS。日本では人気がある
- MySQL : 世界で最も多く使われているRDBMS

### MySQLの歴史
開発：[Mychael Widenius](http://en.wikipedia.org/wiki/Michael_Widenius)  
1995年　　　誕生　スウェーデン「MySQL AB社」がサポート・開発  
2008年2月　サンマイクロシステムズ社が「MySQL AB社」を買収
2010年1月　Oracle社がサンマイクロシステムズ社を買収  

### SQL(Structured Query Language)
#### クエリとSQLについて
　データベースの操作は、ユーザーからデータベースに対してコマンド（命令）を出し、処理する内容を指定する。このコマンドを文字として表したのが**クエリ(query)**。
　クエリを書く時の規則が**SQL(Structured Query Language)**となる。
>機構化した(Structured)、問い合わせ(Query)のための言語(Language)
#### SQLの「方言」
SQLはIBM社が開発した言語だが、現在ではほとんどのRDBMSで使用することが出来る。  
ただし、RDBMSごとにSQLの文法は少しずつ違いがある。

