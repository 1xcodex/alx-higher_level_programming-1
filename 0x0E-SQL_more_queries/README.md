# 0x0E. SQL - More queries 

## Resource

- [How To Create a New User and Grant Permissions in MySQL](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql)
- [How To Use MySQL GRANT Statement To Grant Privileges To a User](https://www.mysqltutorial.org/mysql-grant.aspx)
- [MySQL constraints](https://zetcode.com/mysql/constraints/)
- [SQL technique: subqueries](https://web.csulb.edu/colleges/coe/cecs/dbdesign/dbdesign.php?page=sql/subqueries.php)
- [Basic query operation: the join](https://web.csulb.edu/colleges/coe/cecs/dbdesign/dbdesign.php?page=sql/join.php)
- [SQL technique: multiple joins and the distinct keyword](https://web.csulb.edu/colleges/coe/cecs/dbdesign/dbdesign.php?page=sql/multijoin.php)
- [SQL technique: join types](https://web.csulb.edu/colleges/coe/cecs/dbdesign/dbdesign.php?page=sql/jointypes.php)
- [SQL technique: union and minus](https://web.csulb.edu/colleges/coe/cecs/dbdesign/dbdesign.php?page=sql/setops.php)
- [MySQL Cheat Sheet](https://intellipaat.com/mediaFiles/2019/02/SQL-Commands-Cheat-Sheet.pdf)
- [The Seven Types of SQL Joins](https://tableplus.com/blog/2018/09/a-beginners-guide-to-seven-types-of-sql-joins.html)
- [MySQL Tutorial](https://www.youtube.com/watch?v=yPu6qV5byu4)
- [SQL Style Guide](https://www.sqlstyle.guide/)
- [MySQL 8.0 SQL Statement Syntax](https://dev.mysql.com/doc/refman/8.0/en/sql-statements.html)

---

- Extra resources around relational database model design:
  - [Design](https://www.guru99.com/database-design.html)
  - [Normalization](https://www.guru99.com/database-normalization.html)
  - [ER Modeling](https://www.guru99.com/er-modeling.html)


<details>
<summary>SQL JOINS cheatsheet</summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/y6XJms04/image.png' border='0' alt='image'/></a>
</details>

## Tasks

<details>
<summary><a href="./0-privileges.sql">0. My privileges!</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/HnxfkbM9/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./1-create_user.sql">1. Root user</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/bwG5ZQvm/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./2-create_read_user.sql">2. Read user</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/zGg9d9gC/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./3-force_name.sql">3. Always a name</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/3wSrhstk/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./4-never_empty.sql">4. ID can't be null</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/HsjZxqc7/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./5-unique_id.sql">5. Unique ID</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/RCWpVrnJ/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./6-states.sql">6. States table</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/43MtW04j/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./7-cities.sql">7. Cities table</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/P5HkwfmR/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./8-cities_of_california_subquery.sql">8. Cities of California</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/FKQgv8Xc/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./9-cities_by_state_join.sql">9. Cities by States</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/FsSwxfmx/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./10-genre_id_by_show.sql">10. Genre ID by show</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/bN0nXhhj/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./11-genre_id_all_shows.sql">11. Genre ID for all shows</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/4dpdQ7yb/image.png' border='0' alt='image'/></a>
</details>