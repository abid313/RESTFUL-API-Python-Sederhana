GET, PUT, PATCH, DELETE

Untuk post/create data baru bisa menggunakan put.

Contoh Menggunakan Postman:

{{base_url}}/video/{id}

PUT:
{
    "name"  : "abid",
    "views" : 10000,
    "likes" : 80
}

PATCH:
{
    "name"  : "test",
    "views" : 10,
    "likes" : 1
}
