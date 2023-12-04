 # Students CRUD API

 ## artisan parancsok
 Új migráció létrehozása
 ```php artisan make:migration create_students_table```

 Migráció lefuttatása 
 ```php artisan migrate``
 
 Utolsó migráció visszavonása
 ```php artisan migrate:rollback```


 Elkezdeni előröl(kitörli az összes táblát, és létrehozza újra)
 ```php artisan migrate:fresh```

 Modell létrhozása 
 ````php artisan make:model Student``
 ajánlott:
 - model Nagybetűvel kezdődik és egyes szám, hozzá a tábla kisbetűs többesszám
 - angolul csinálni


 Factory létrehozása ( fake adatok generálása)
```php artisan make:factory```


Seeder futtatása
```php artisan db:seed```

migráció és seedelés egyben
 ```php artisan migrate --seed```
 ```php artisan migrate:fresh --seed```

 Controller osztály létrehozása
 ```php artisan make:controller StudentController```

 Api metodusokkal együtt
 ```php artisan make:controller StudentController --api```

 All in one:
```php artisan make:model Teacher -mfc --api```


## ThunderClient export 
thinder-collection_students.json
