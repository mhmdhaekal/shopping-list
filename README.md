main url : http://muhammad-haekal22-tutorial.pbp.cs.ui.ac.id

backup url (in case above doesn't work or) : https://shopping-list-haekal.fly.dev

notes:
The main URL is already working, but I think there is an issue with the database (possibly due to migration), as I'm
encountering errors when trying to log in, the error look like this:

```
ProgrammingError at /
column main_product.user_id does not exist
LINE 1: ...n_product"."price", "main_product"."description", "main_prod...
```

However,this error is not occuring on the backup url or localhost

REV: 20 September 10.14 PM