# gin-api-docker

[![GoDoc](https://img.shields.io/static/v1?label=godoc&message=reference&color=blue)](https://github.com/gin-gonic/gin)

Implementation of REST API built with GIN Framework.
API Endpoints setup on sqlite3 database capable of CRUDops.

<img src="https://www.scylladb.com/wp-content/uploads/BlinkJump_Animation_07_Shadow_193b6c-1.gif" width="152" height="191"/>

https://github.com/gin-gonic/gin

```
[GIN-debug] GET    /products                 --> main.getProducts (3 handlers)
[GIN-debug] GET    /products/:id             --> main.getProductById (3 handlers)
[GIN-debug] POST   /products                 --> main.insertProduct (3 handlers)
[GIN-debug] PUT    /products/:id             --> main.updateProduct (3 handlers)
[GIN-debug] DELETE /products/:id             --> main.deleteProduct (3 handlers)
[GIN-debug] Listening and serving HTTP on :1991
```
 
https://tutorialedge.net/golang/go-docker-tutorial/

You can build docker with this:
`` docker build -t my-go-app . ``

