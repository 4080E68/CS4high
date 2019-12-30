# CRUD
```
在資料庫中有四種常用函式：
   新增（Create）
   讀取（Read）
   更新（Update）
   刪除（Delete）
```

# 資料階層
```
   第一階層 Bit(位元)
   第二階層 bytes(字元)
   第三階層 fidle(欄位)
   第四階層 records(紀錄)
   第五階層 files(檔案)
   第六階層 database(資料庫)
```

# 資料庫管理系統（database management system，DBMS）
```
   通常資料庫管理師會使用資料庫管理系統來建立資料庫系統。
   資料庫管理系統是一套電腦程式，以控制資料庫的分類及資料的存取。
   具有代表性的資料管理系統有：Oracle、Microsoft SQL Server、Access、MySQL及PostgreSQL等。
```
# 檔案處理系統 vs. 資料庫


### 檔案處理系統優缺點
```
   缺點:舉有重複的資料、以及資料被隔離(無法及時跟新)

   優點:所需要的技術和記憶體比資料庫來的少
```


### 資料庫優缺點
```
   優點: 降低資料重複性、改進資料完整性、資料共享、更容易存取、縮短開發時間

   缺點: 比檔案處理系統更為複雜、也需要更多的記憶體和處理能力、比檔案處理系統更容易被入侵
```
# 資料庫理論

### 資料模型（data model）

```
   Network 
   Hierarchical data model
   relational Data Model
   Object-oriented data model
   Multi-dimensioncal data model[data warehouse  vs Data Mall]
```

# 資料庫管理系統

## SQL(Structured Query Language) 

### DDL
```
    (資料定義語言（Data Definition Language)
    負責資料結構定義與資料庫物件定義的語言
    由CREATE、ALTER與DROP三個語法所組成
```
### DDL
```
    (資料操縱語言（Data Manipulation Language)
    是用於資料庫操作，對資料庫其中的物件和資料執行存取工作的編程語句
    以INSERT、UPDATE、DELETE三種指令為核心
    分別代表插入(意指新增或建立)、更新(修改)與刪除(銷毀)
    以四個漢字：增 查 改 刪 來略稱。
```
### DCL
```
    (資料控制語言 (Data Control Language) )
    在SQL語言中，是一種可對資料存取權進行控制的指令
    由 GRANT 和 REVOKE 兩個指令組成
```

# 大數據與新興資料庫

### 3V
```
   Volume   (資料大小）
   Velocity (資料輸入輸出的速度）
   Variety  (多樣性）
```
### 5V
```
   Volume   (資料大小）
   Velocity (資料輸入輸出的速度）
   Variety  (資料的多樣性）
   Value    (資料的值)
   Veracity (資料的真實性)
```

## 揮發性記憶體
```
當電流中斷後，所儲存的資料便會消失的電腦記憶體。
```
## 非揮發性記憶體
```
是指當電流關掉後，所儲存的資料不會消失的電腦記憶體。
```



















