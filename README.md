# rest-metapi
Dynamic REST API:
Just create a mongoDB collection and it's all.. you got a RESTful Web Service to manage that collection.
+ Avoid any back-end implementation.
+ Feel free to focus to the beauty front-end.
+ No additional commands needed.

## Service Endpoints
Every RESTful Webservice includes this endpoints:

+ findAll
```java
    GET: /{collection}
```

+ getById
```java
    GET: /{collection}/{id}
```

+ insert
```java
    POST: /{collection}
```

+ query
```java
    POST: /{collection}/query
    //REQUIRES JSON Body request with search prototype
```

+ update
```java
    PUT: /{collection}/{id}
```

+ delete
```java
    DELETE: /{collection}/{id}
```