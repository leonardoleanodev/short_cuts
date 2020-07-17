# Postgres Shortcuts

## BACKUP
`pg_dump -U user -h host -d database_name > backup_dev.sql`
## CREATE DATABASE
`CREATE DATABASE nome_banco;`
## RESTORE
```
psql -U usaurio -d nome_banco -h host  < backup_dev.sql

SELECT
	pg_terminate_backend(pg_stat_activity.pid)
FROM
	pg_stat_activity
WHERE
	pg_stat_activity.datname = 'dataname'
	AND pid <> pg_backend_pid();
```
