Docker(docker-composer)でmysqlを使う！

参考：https://qiita.com/A-Kira/items/f401aea261693c395966

手順
1. `git clone https://github.com/y-keisuke/mysql_docker.git`
2. このディレクトリ移動
3. `docker-compose up -d`
4. `docker-compose ps`で確認
5. `init-mysql.sh`  

サーバーへログイン
```
mysql -h 127.0.0.1 -p test_database -u root -p
```
password
```
root
```

phpmyadmin
```$xslt
http://localhost:8080/
```