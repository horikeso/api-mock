## API MOCK Example using GitHub

### Example

```
curl -i -X GET \
   -H "Content-Type:application/json" \
 'https://horikeso.github.io/api-mock/auth/post.json'
```

```
{"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MSwibmFtZSI6ImhvcmlrZXNvIn0.L-gvKEaDxRlYytj7biTbONFCc_LsmVP6xSHvDomdBy8"}
```

```
curl -i -X GET \
   -H "Content-Type:application/json" \
 'https://horikeso.github.io/api-mock/auth/tokens/verify.json'
```

```
{"is_valid": true}
```


```
curl -i -X GET \
   -H "Content-Type:application/json" \
 'https://horikeso.github.io/api-mock/users/1.json'
```

```
{
    "id": 1,
    "name": "horikeso",
    "address": "Japan",
    "gender": 1,
    "age": null,
    "authenticatedAt": "2021-09-17 12:00:00",
    "createdAt": "2021-09-17 00:00:00",
    "remarks": "API MOCK EXAMPLE using GitHub"
}
```

```
curl -i -X GET \
   -H "Content-Type:application/json" \
 'https://horikeso.github.io/api-mock/selects/genders.json'
```

```
[
   {"id": 1, "name": "male"},
   {"id": 2, "name": "female"}
]
```


