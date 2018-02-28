# Using PostgreSQL with Ruby on Rails

## set up Posgres

### create a database user

```
sudo -u postgres createuser -s pguser
```

#### set a password for `pguser`
```bash
sudo -u postgres psql

postgres=# \password pguser #then enter in a password

# quit postgres
postgres=# \q
``` 

### set up your database config file

open up your `config/database.yml` file and place the following code in it:
```yml
host: localhost
username: pguser
password: pguser_password //this is the password you created in the last step
```

## 