# REST API  BOOKS

Service ini tidak menggunakan database melainkan array dalam file books.js.

## URL Aplikasi

Akses url berikut untuk menggunakan api

```bash
http://13.212.201.230:9000/
```

## Save Books
- Method : POST
- URL : /books

Body Request :

```json
{
    "name": string,
    "year": number,
    "author": string,
    "summary": string,
    "publisher": string,
    "pageCount": number,
    "readPage": number,
    "reading": boolean
}
```
Body Response :

```json
{
    {
    "status": "success",
    "message": "Buku berhasil ditambahkan",
    "data": {
        "bookId": "1L7ZtDUFeGs7VlEt"
    }
}
}
```

