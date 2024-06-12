# SQL-discoveries-
Show the total amount of male patients and the total amount of female patients in the patients table.
Display the two results in the same row.
```sql
SELECT 
  SUM(Gender = 'M') as male_count, 
  SUM(Gender = 'F') AS female_count
FROM patients
```
result 
![Screenshot from 2024-06-12 17-10-26](https://github.com/ChinmayCP2/SQL-discoveries-/assets/171817542/85d1676a-0fc1-413c-b642-7d8a5430e258)

