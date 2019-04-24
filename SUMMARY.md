# Summary

* [MySQL 速成指南](README.md)
* [安装](00-installation.md)
* [密码](01-password.md)
* [客户端](02-client.md)

## SQL 语句语法
* [数据定义语言](data-definition/README.md)
    - [CREATE](data-definition/create.md)
    - [ALTER](data-definition/alter.md)
    - [DROP](data-definition/drop.md)

* [数据操纵语言](data-manipulation/README.md)
    - [INSERT](data-manipulation/insert.md)
    - [SELECT](data-manipulation/select.md)
    - [UPDATE](data-manipulation/update.md)
    - [DELETE](data-manipulation/delete.md)

* [数据控制语言](data-control/README.md)

* [数据查询语言](data-query/README.md)
* [事务处理和锁定]

## 配置
* [主从复制](00-configuration/00-replication.md)
* [读写分离](00-configuration/01-write-read.md)

## 优化
* [索引优化](01-optimization/README.md)

## MySQL 程序概述
* [mysqld] SQL 守護進程，MySQL 服務器
* [mysqld_safe] 服務器啓動脚本，嘗試啓動 mysqld
* [mysql.server] 服務器啓動脚本
* [mysqld_multi] 服務器啓動脚本
* [mysql_install_db] 初始化數據目錄和初始數據庫
* [comp_err]
* [mysql] 命令行客戶程序，用於交互式或以批處理模式執行 SQL 語句
* [mysqladmin](02-tools/mysqladmin.md) 管理功能的客戶程序
* [mysqlcheck] 執行表維護操作
* [mysqldump] 和 [mysqlhotcopy] 負責數據庫備份
* [mysqlimport] 和 [mysqlshow] 顯示信息數據庫和表的相關信息
* [myisamchk] 執行表維護操作
* [myisampack] 產生壓縮、只讀的表
* [mysqlbinlog] 處理二進制日志文件的實用工具
* [perror] 顯示錯誤代碼的含義
