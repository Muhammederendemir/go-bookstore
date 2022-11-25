# 🎯 Go Book Store

<img src="https://github.com/Muhammederendemir/go-bookstore/blob/main/image/go-bookstore.jpg">

## 📌 Case

I have a Book Struct and I will create, read, update, delete operation in Mysql Database System.

## 📌 Run

```yaml
cd /cmd/main/
```

```yaml
go build
```

```yaml
go run main.go
```

## 📌 Get Books Service 

* http://localhost:9090/book  

## 📌 Get Book Service

* http://localhost:9090/book/{id} 

## 📌 Create Book Service

* http://localhost:8080/book  

## 📌 Update Book Service

* http://localhost:9090/book/{id} 

## 📌 Delete Book Service

* http://localhost:9090/book/{id} 


## 📌 Request Body

```JSON
{
	"Name":"Go book",
	"Author": "Muhammed Eren Demir",
	"Publication":"DR"
}
```

## 📌 Response Body

```JSON
[
    {
        "ID": 1,
        "CreatedAt": "2022-11-25T06:47:18Z",
        "UpdatedAt": "2022-11-25T06:47:18Z",
        "DeletedAt": null,
        "Name": "Go book",
        "author": "Muhammed Eren Demir",
        "publication": "DR"
    }
]
```

## 📌 Packages

- encoding/json
- net/http
- strconv
- io/ioutil
- github.com/gorilla/mux
- github.com/jinzhu/gorm/dialects/mysql

## 📌 Reources
* https://www.youtube.com/watch?v=jFfo23yIWac&ab_channel=freeCodeCamp.org

