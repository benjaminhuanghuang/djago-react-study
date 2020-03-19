## Database migration

```
  python manage.py makemigrations
```
- Generates migration files for later use
- Use current model fields and current database tabels


```
  python manage.py migrate <appname> <nubmer>
```
- Runs all migratons that haven't been run yet
