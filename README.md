# Azurian
#### _APIdemo_

##### getUser

Metodo para obtener una lista de Usuario

```
curl --location --request GET 'http://localhost:8080/azurian/v1/users'
```

##### getUserById

Metodo para obtener un Usuario

```
curl --location --request GET 'http://localhost:8080/azurian/v1/user/e10b003-6dee-4e1c-98de-292d0ac2ae1a
```

##### deleteUserById

Metodo para eliminar un Usuario

```
curl --location --request DELETE 'http://localhost:8080/azurian/v1/user/797f210-fd2e-4af4-9309-9078c10d18b7'
```

##### createUser

Metodo para crear un Usuario

```
curl --location --request PUT 'http://localhost:8080/azurian/v1/users' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "juan",
    "lastName": "achurian",
    "birthDate": "1957-02-05T00:00:00.000Z",
    "phoneNumber": "987654323",
    "phoneCountryCode": "56",
    "country": "BR",
    "email": "juan.perez@gmail.com"
}'
```

##### updateUser

Metodo para editar un Usuario

```
curl --location --request POST 'http://localhost:8080/azurian/v1/users' \
--header 'Content-Type: application/json' \
--data-raw '{
    "userId": "e10b003-6dee-4e1c-98de-292d0ac2ae1a",
    "firstName": "werwer",
    "lastName": "Dicaprssssio",
    "birthDate": "1991-02-27",
    "phoneNumber": "987677777",
    "phoneCountryCode": "56",
    "country": "RU",
    "email": "werwer.Dicaprssssio.ru@azurian.cl"
}'
```



