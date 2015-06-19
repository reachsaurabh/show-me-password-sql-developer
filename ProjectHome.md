
---

# Warning: #

# This project was moved from Google Code to [GitHub](https://github.com/tomecode/Show-Me-Password) #

# A new official website of the project is: [Show Me Password](http://show-me-password.tomecode.com/) #


---



The "Show me password" is a simple extension for the [Oracle SQL Developer](http://www.oracle.com/technetwork/developer-tools/sql-developer/overview/index.html) i.e. tool that decrypts all saved (encrypted) password for database connections in SQL Developer.

| **SQL Developer Version** | **Extension Version** | **Download** |
|:--------------------------|:----------------------|:-------------|
| 4.xx                      | 1.0.0                 | [Download Show Me Password for SQL Developer 4.x](http://show-me-password-sql-developer.googlecode.com/files/ShowMePasswordSQLDeveloper4_v1.0.0.zip) |
| 3.xx                      | 1.2                   | [Download Show Me Password  for SQL Developer 3.x](http://show-me-password-sql-developer.googlecode.com/files/showMePassword_bin_1_2.zip) |
| 2.xx                      | 1.2                   | [Download Show Me Password  for SQL Developer 2.x](http://show-me-password-sql-developer.googlecode.com/files/showMePassword_bin_1_2.zip) |


---

# Show Me password - extension for Oracle SQL Developer v4.x #
Release Notes:
  * Version: 1.0.0
    1. first version
    1. [bug fix](http://code.google.com/p/show-me-password-sql-developer/issues/detail?id=2)
    1. requirements: Java 1.7 or higher, SQL Developer 4

![http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloper4_win.png](http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloper4_win.png)


### How To Install ###
  * Download the [extension](http://show-me-password-sql-developer.googlecode.com/files/ShowMeasswordSQLDeveloper4_v2.zip) to your machine (the extension will be packaged as a zip file - pls. don't unzip the extension;) ).
  * In SQL Developer 4 use the help->Check for updates... and instead of choosing from the existing update centers, choose the "Install From Local File" option, and point to the zip file you have downloaded
  * Restart SQL Developer to complete the extension installation

If you click menu "Show Me Password", then displays a window that contains a table (with columns: connection name, ,db host, SID, user name and decrypted (saved) password to database) with list of all stored connections to databases in SQL Developer.


---


# Show Me password - extension for Oracle SQL Developer v3.x, v2.x #
Release Notes:
  * Version: 1.2
    1. new column: Service Name
    1. [bug fix](http://code.google.com/p/show-me-password-sql-developer/issues/detail?id=1&can=1)
    1. requirements: Java 1.6 or higher, SQL Developer 2.x or 3.x
  * Version: 1.1
    1. changes in GUI
    1. filter by DB connection name
    1. display: hostname and DB SID
    1. sorting columns
    1. requirements: Java 1.6 or higher, SQL Developer 2 or 3
  * Version: 1.0
    1. first version
    1. requirements: Java 1.5 or higher, SQL Developer 2.x or 3.x

### How To Install ###
Download the [extension](http://show-me-password-sql-developer.googlecode.com/files/showMePassword_bin_1_2.zip) , unzip it and copy JAR file it to **_$SQL\_DEVELOPER/sqldeveloper/extensions/_** and run SQL Developer.
In the menu **“File”** you will see new menu item **“Show Me Database Password”**

![http://www.tomecode.com/img/projects/show-me-password-sqldeveloper-ext/showMePasswordMenu.png](http://www.tomecode.com/img/projects/show-me-password-sqldeveloper-ext/showMePasswordMenu.png)


If you click menu "Show Me database password", then displays a window that contains a table (with columns: connection name, ,db host, SID, user name and decrypted (saved) password to database) with list of all stored connections to databases in SQL Developer.


_Note for Mac OS Version: copy extension to SQLDeveloper.app/Contents/Resources/sqldeveloper/sqldeveloper_



**Show Me Password SQL Developer on Windows**

![http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloperWindows.png](http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloperWindows.png)

#### Install Video (Windows): ####
<a href='http://www.youtube.com/watch?feature=player_embedded&v=E1AschZKqEQ' target='_blank'><img src='http://img.youtube.com/vi/E1AschZKqEQ/0.jpg' width='425' height=344 /></a>

**Show Me Password SQL Developer on Linux**

![http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloperLinux.png](http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloperLinux.png)


**Show Me Password SQL Developer on Mac OS X**

![http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloperMacOsX.png](http://show-me-password-sql-developer.googlecode.com/svn/wiki/showMePasswordSqlDeveloperMacOsX.png)

#### Install Video (MAC OS X): ####
<a href='http://www.youtube.com/watch?feature=player_embedded&v=3v-8-MGuqYk' target='_blank'><img src='http://img.youtube.com/vi/3v-8-MGuqYk/0.jpg' width='425' height=344 /></a>



---

**Please, send me(tomecode AT tomecode DOT com) either your ideas or any bugs you will find. Then I will try to fix it and incorporate to the new version as soon as possible.**

---
