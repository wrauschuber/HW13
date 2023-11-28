# HW12-BAIS3400

BAIS:3400/6400 - homework using App Services, MySQL, Active Directory, and Key Vault to create a database driven web application.

---

## To Do List

- [ ] Create a database helper class to create a connection, execute a query and close the connection - ideas in email (11/10/2023)

https://zetcode.com/python/pymysql/  
https://www.tutorialspoint.com/python/python_database_access.htm

```
mydb = MySQLdb.connect(host=host, user=user, passwd=passwd, db=database, charset="utf8")
cursor = mydb.cursor()
query = "INSERT INTO tablename (text_for_field1, text_for_field2, text_for_field3, text_for_field4) VALUES (%s, %s, %s, %s)"
cursor.execute(query, (field1, field2, field3, field4))
mydb.commit()
cursor.close()
mydb.close()
```

- [ ] Is logging appropriate?
- [ ] Can I read other logs with /diagnostics?
- [ ] Create a navbar
- [ ] Create a robots.txt
- [ ] Create an "accept" for data collection
- [ ] Create some queries and menu item for most popular, shortest, longest, etc.
- [ ] Individual movie images
- [ ] Updated movies data
- [ ] Properly constructed database tables
- [ ] Add a "no record found" if no movies are found on a search
- [ ] Add custom error pages
- [ ] Add an admin interface
- [ ] Update to Flask 3

---

## Change log

11/10/2023 - Added /diagnostics
11/10/2023 - Added logging
11/10/2023 - Added Bootstrap 5.2 for styling
11/10/2023 - Web app is loaded and working
