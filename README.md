# SQL Server

<details><summary>DROP DATABASE</summary>

```sql
USE [master]
GO

ALTER DATABASE [Blog] SET SINGLE_USER WITH ROLLBACK IMMEDIATE
GO

DROP DATABASE [Blog]
GO
```
  
</details>
