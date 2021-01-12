# Oracle Docker (Compose) Template

   ```
1. Grab a pint of :coffee: and wait until the database setup including dump import is done.

The password for all Oracle system accounts (`SYSTEM`, `SYS`, `PDBADMIN`) is `oracle`

The `db.*` properties for SAP Commerce are:

```properties
db.url=jdbc:oracle:thin:@localhost:1521/ORCLPDB1
db.driver=oracle.jdbc.driver.OracleDriver
db.username=localdev
db.password=localdev
```
