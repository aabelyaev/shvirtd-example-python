# Домашнее задание к занятию 5. «Практическое применение Docker»

## Задние 2
aabelyaev@aabelyaev-Redmi-Book-Pro-15-2022:~/studynetelogy/studynetelogy/docker-homework-5$ yc container image scan crpg2ie0lajiv8os7tdc         
done (2m2s)
id: chehhhlkh695h******
image_id: crpg2ie0laji******
scanned_at: "2024-03-04T08:50:18.839Z"
status: READY
vulnerabilities:
  critical: "1"
  high: "19"
  medium: "23"
  low: "67"

## Задние 3
Команда docker logs shvirtd-example-python-web-1 выводит такую проблему как её решить?

The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "/app/main.py", line 14, in <module>
    db = mysql.connector.connect(
  File "/usr/local/lib/python3.9/site-packages/mysql/connector/pooling.py", line 322, in connect
    return CMySQLConnection(*args, **kwargs)
  File "/usr/local/lib/python3.9/site-packages/mysql/connector/connection_cext.py", line 140, in __init__
    self.connect(**kwargs)
  File "/usr/local/lib/python3.9/site-packages/mysql/connector/abstracts.py", line 1363, in connect
    self._open_connection()
  File "/usr/local/lib/python3.9/site-packages/mysql/connector/connection_cext.py", line 328, in _open_connection
    raise get_mysql_exception(
mysql.connector.errors.DatabaseError: 2003 (HY000): Can't connect to MySQL server on 'localhost:3306' (99)

## Задние 4


## Задние 5

