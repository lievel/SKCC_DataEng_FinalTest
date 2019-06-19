## MySQL 설치 및 설정

### Show hostname database server

![ex_screenshot](./캡처_mysql_hostname_version.PNG)

### Show database server version

![ex_screenshot](./캡처_mysql_hostname_version.PNG)

### List all the databases in the server

![ex_screenshot](./캡처_mysql_databases_list.PNG)


### create sample tables and grant user

#### Databases, User 생성 및 권한 부여
<pre>
CREATE DATABASE test;

create user 'training'@'localhost' identified by 'training';

grant all privileges on *.* to 'training'@'localhost';

FLUSH PRIVILEGES;
</pre>

#### 샘플 sql 전송 및 mysql에 로드
<pre>
pscp d:/authors-23-04-2019-02-34-beta.sql centos@13.124.12.181:/home/centos
pscp d:/posts23-04-2019-02-44.sql centos@13.124.12.181:/home/centos

source /home/centos/authors-23-04-2019-02-34-beta.sql;
source /home/centos/posts23-04-2019-02-44.sql;

</pre>

![ex_screenshot](./캡처_mysql_authors_post_table.PNG)

## Extract tables authors and posts from the databases and create Hive tables.
