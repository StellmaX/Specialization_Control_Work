# Итоговая контрольная работа по блоку специализация

## Операционные системы и виртуализация (Linux)

```

User@User-VirtualBox:\~$ cd Nursery/

User@User-VirtualBox:\~/Nursery$ cat \> Pets.txt

Собака

Кошка

Хомяк

User@User-VirtualBox:\~/Nursery$ cat \> PackAnimals.txt

Лошадь   	 

Верблюд

Оcел

User@User-VirtualBox:\~/Nursery$ cat Pets.txt PackAnimals.txt \> Animals.txt

User@User-VirtualBox:\~/Nursery$ cat Animals.txt

Собака

Кошка

Хомяк

Лошадь

Верблюд

Оcел

User@User-VirtualBox:\~/Nursery$ mv Animals.txt HumanFriends.txt

User@User-VirtualBox:\~/Nursery$ ls

HumanFriends.txt  PackAnimals.txt  Pets.txt  
User@User-VirtualBox:\~/Nursery$ mkdir PetsDirectory

User@User-VirtualBox:\~/Nursery$ mv HumanFriends.txt PetsDirectory/

User@User-VirtualBox:\~/Nursery$ cd PetsDirectory/

User@User-VirtualBox:\~/Nursery/PetsDirectory$ ls

HumanFriends.txt

User@User-VirtualBox:\~/Nursery/PetsDirectory$ cd ..

User@User-VirtualBox:\~$ sudo apt-get update

[sudo] пароль для User:

http://ru.archive.ubuntu.com/ubuntu jammy InRelease

http://ru.archive.ubuntu.com/ubuntu jammy-updates InRelease \[128 kB\]                                                      	 

http://repo.mysql.com/apt/ubuntu jammy InRelease                                                                          	 

http://security.ubuntu.com/ubuntu jammy-security InRelease \[129 kB\]                                                       	 

https://ppa.launchpadcontent.net/deadsnakes/ppa/ubuntu jammy InRelease                                   	 

http://ru.archive.ubuntu.com/ubuntu jammy-backports InRelease                                            	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main i386 Packages \[703 kB\]

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 Packages \[2 062 kB\]

http://security.ubuntu.com/ubuntu jammy-security/main i386 Packages \[544 kB\]             	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main Translation-en \[356 kB\]

http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 c-n-f Metadata \[17,8 kB\]	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/restricted amd64 Packages \[2 499 kB\]	 

http://security.ubuntu.com/ubuntu jammy-security/main amd64 Packages \[1 844 kB\]                      	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/restricted Translation-en \[430 kB\]

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe i386 Packages \[733 kB\]         	 

http://security.ubuntu.com/ubuntu jammy-security/main Translation-en \[298 kB\]      	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 Packages \[1 125 kB\]  	 

http://security.ubuntu.com/ubuntu jammy-security/main amd64 c-n-f Metadata \[13,3 kB\]     	 

http://security.ubuntu.com/ubuntu jammy-security/restricted amd64 Packages \[2 439 kB\]       	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe Translation-en \[262 kB\]               	 

http://security.ubuntu.com/ubuntu jammy-security/restricted Translation-en \[420 kB\]                  	 

http://security.ubuntu.com/ubuntu jammy-security/universe amd64 Packages \[906 kB\]             	 

http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 c-n-f Metadata \[26,1 kB\]    	 

http://security.ubuntu.com/ubuntu jammy-security/universe i386 Packages \[629 kB\]        	 

http://security.ubuntu.com/ubuntu jammy-security/universe Translation-en \[177 kB\]

http://security.ubuntu.com/ubuntu jammy-security/universe amd64 c-n-f Metadata \[19,3 kB\]

Получено 15,8 MB за 6с (2 451 kB/s)                                                                                             	 

Чтение списков пакетов… Готово

User@User-VirtualBox:\~$ sudo apt-get install mysql-server

Чтение списков пакетов… Готово

Построение дерева зависимостей… Готово

Чтение информации о состоянии… Готово    	 

Уже установлен пакет mysql-server самой новой версии (8.0.39-1ubuntu22.04).

Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 0 пакетов, и 44 пакетов не обновлено.

User@User-VirtualBox:~$ mysql \--version

mysql  Ver 8.0.39 for Linux on x86\_64 (MySQL Community Server \- GPL)

User@User-VirtualBox:~$ sudo apt-get install cowsay

Чтение списков пакетов… Готово

Построение дерева зависимостей… Готово

Чтение информации о состоянии… Готово    	 

Предлагаемые пакеты:

  filters cowsay-off

Следующие НОВЫЕ пакеты будут установлены:

  cowsay

Обновлено 0 пакетов, установлено 1 новых пакетов, для удаления отмечено 0 пакетов, и 44 пакетов не обновлено.

Необходимо скачать 18,6 kB архивов.

После данной операции объём занятого дискового пространства возрастёт на 93,2 kB.

http://ru.archive.ubuntu.com/ubuntu jammy/universe amd64 cowsay all 3.03+dfsg2-8 \[18,6 kB\]

Получено 18,6 kB за 0с (47,5 kB/s)

Выбор ранее не выбранного пакета cowsay.

(Чтение базы данных … на данный момент установлено 229806 файлов и каталогов.)

Подготовка к распаковке …/cowsay\_3.03+dfsg2-8\_all.deb …

Распаковывается cowsay (3.03+dfsg2-8) …

Настраивается пакет cowsay (3.03+dfsg2-8) …

Обрабатываются триггеры для man-db (2.10.2-1) …

User@User-VirtualBox:~$ cowsay "Привет!"

 \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

\< Привет! \>

 \---------------

    	\\   ^\_\_^

     	\\  (oo)\\\_\_\_\_\_\_\_

        	(\_\_)\\   	)\\/\\

            	||----w |

            	|| 	||


User@User-VirtualBox:~$ sudo apt-get remove cowsay

Чтение списков пакетов… Готово

Построение дерева зависимостей… Готово

Чтение информации о состоянии… Готово    	 

Следующие пакеты будут УДАЛЕНЫ:

  cowsay

Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 1 пакетов, и 44 пакетов не обновлено.

После данной операции объём занятого дискового пространства уменьшится на 93,2 kB.

Хотите продолжить? \[Д/н\] y

(Чтение базы данных … на данный момент установлено 229866 файлов и каталогов.)

Удаляется cowsay (3.03+dfsg2-8) …

Обрабатываются триггеры для man-db (2.10.2-1) …

User@User-VirtualBox:~$ history \> history.txt

 1823  cd Nursery/

 1824  cat \> Pets.txt

 1825  cat \> PackAnimals.txt

 1826  cat Pets.txt PackAnimals.txt \> Animals.txt

 1827  cat Animals.txt

 1828  mv Animals.txt HumanFriends.txt

 1829  ls

 1830  mkdir PetsDirectory

 1831  mv HumanFriends.txt PetsDirectory/

 1832  cd PetsDirectory/

 1833  ls
 
 1834  cd..

 1835  sudo apt-get update

 1836  sudo apt-get intstall mysql-server

 1837  sudo apt-get install mysql-server

 1838  mysql \--version

 1839  sudo apt-get install cowsay

 1840 cowsay "Здарова отец

 1841  sudo apt-get remove cowsay

 1842  history \> history.txt

```

------------------------------------------------------------------------------------------------------------------------------------------------------

## Объектно-ориентированное программирование

```
mysql\> CREATE DATABASE HumanFriends;

Query OK, 1 row affected (0,11 sec)

mysql\> USE HumanFriends;

Database changed

mysql\>	CREATE TABLE Pets (

	\-\>    	ID INT AUTO\_INCREMENT PRIMARY KEY,

	\-\>    	Name VARCHAR(50),

	\-\>    	Type VARCHAR(20),

	\-\>    	BirthDate DATE,

	\-\>    	Commands TEXT

	\-\>	);

Query OK, 0 rows affected (0,29 sec)

mysql\>

mysql\>	CREATE TABLE PackAnimals (

	\-\>    	ID INT AUTO\_INCREMENT PRIMARY KEY,

	\-\>    	Name VARCHAR(50),

	\-\>    	Type VARCHAR(20),

	\-\>    	BirthDate DATE,

	\-\>    	Commands TEXT

	\-\>	);

Query OK, 0 rows affected (0,25 sec)

mysql\>    

mysql\> INSERT INTO Pets (Name, Type, BirthDate, Commands) VALUES

	\-\> ('Bobick', 'Dog', '2021-10-11', 'Sit, Stay, Play dead'),

	\-\> ('Murzik', 'Cat', '2020-08-13', 'Sit, Jump, Down'),

	\-\> ('Bak', 'Hamster', '2022-12-15', 'Play dead'),
	
	\-\> ('Nicole', 'Hamster', '2022-12-15', 'Down'),

	\-\> ('Mukhtar', 'Dog', '2015-01-01', 'Bite, Drop it, Speak'),

	\-\> ('Kesha', 'Cat', '2018-08-13', 'Paw, Wait, Heel'),

	\-\> ('Zina', 'Dog', '2013-02-19', 'Speak, Stay, Wait'),

	\-\> ('Marusya', 'Cat', '2016-09-22', 'Meow, Scratch, Jump');

Query OK, 8 rows affected (0,15 sec)

Records: 8  Duplicates: 0  Warnings: 0

mysql\> INSERT INTO PackAnimals (Name, Type, BirthDate, Commands) VALUES

	\-\> ('Coast', 'Horse', '2019-06-14', 'Gallop, Jump, Trot'),

	\-\> ('Brick', 'Camel', '2018-11-28', 'Carry Load, Walk'),

	\-\> ('Donkey', 'Donkey', '2019-04-13', 'Bray, Walk, Carry Load'),

	\-\> ('Matilda', 'Horse', '2014-08-24', 'Gallop, Canter'),

	\-\> ('Thorn', 'Camel', '2016-01-19', 'Walk, Down'),

	\-\> ('Egor', 'Donkey', '2013-09-18', 'Stop, Walk, Bray'),

	\-\> ('Wind', 'Horse', '2019-12-12', 'Back, Gallop, Walk'),

	\-\> ('Pharaoh', 'Camel', '2012-02-17', 'Down, Walk');

Query OK, 8 rows affected (0,06 sec)

Records: 8  Duplicates: 0  Warnings: 0

mysql\> DELETE FROM PackAnimals WHERE Type \= 'Camel';

Query OK, 3 rows affected (0,02 sec)

mysql\> CREATE TABLE YoungAnimals AS

	\-\> SELECT

    \-\>   ID,

    \-\>   Name,

    \-\>   Type,

    \-\>   BirthDate,

    \-\>   Commands,

    \-\>   FLOOR(DATEDIFF(CURDATE(), BirthDate) / 30) AS AgeInMonths

    \-\> FROM

    \-\>   Pets

    \-\> WHERE

    \-\>   DATEDIFF(CURDATE(), BirthDate) BETWEEN 365 AND 1095

    \-\> UNION ALL

    \-\> SELECT

    \-\>   ID,

    \-\>   Name,

    \-\>   Type,

    \-\>   BirthDate,

    \-\>   Commands,

    \-\>   FLOOR(DATEDIFF(CURDATE(), BirthDate) / 30) AS AgeInMonths

    \-\> FROM

    \-\>   PackAnimals

    \-\> WHERE

    \-\>   DATEDIFF(CURDATE(), BirthDate) BETWEEN 365 AND 1095;
    
Query OK, 3 rows affected (0,18 sec)

Records: 0  Duplicates: 0  Warnings: 0

mysql\> CREATE TABLE AllAnimals AS

    \-\> SELECT

    \-\>   ID,

    \-\>   Name,

    \-\>   Type,

    \-\>   BirthDate,

    \-\>   Commands,

    \-\>   FLOOR(DATEDIFF(CURDATE(), BirthDate) / 30) AS AgeInMonths,

    \-\>   'Pets' AS Source

    \-\> FROM

    \-\>   Pets

    \-\> UNION ALL

    \-\> SELECT

    \-\>   ID,

    \-\>   Name,

    \-\>   Type,

    \-\>   BirthDate,

    \-\>   Commands,

    \-\>   FLOOR(DATEDIFF(CURDATE(), BirthDate) / 30) AS AgeInMonths,

    \-\>   'PackAnimals' AS Source

    \-\> FROM

    \-\>   PackAnimals

    \-\> UNION ALL

    \-\> SELECT

    \-\>   ID,

    \-\>   Name,

    \-\>   Type,

    \-\>   BirthDate,

    \-\>   Commands,

    \-\>   FLOOR(DATEDIFF(CURDATE(), BirthDate) / 30) AS AgeInMonths,

    \-\>   'YoungAnimals' AS Source

    \-\> FROM

    \-\>   YoungAnimals;

Query OK, 16 rows affected (0,12 sec)
```
Работу выполнял Стельмах Алексей Александрович, 04.10.24, 6378