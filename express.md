# Express
![logo](https://assenfuego.com/dist/dev/express.svg)

<br>

## Route
How an app responds to a request to a particular endpoint.

* `Route Methods`: CRUD
* `Route Paramter`: Stored in params `(req.params)`

`Route`: Paths and Methods
```
app.get("/books", (req,res) => {
  res.send("Welcome)
})
```
`Path`: "/books"
`Method`: .get
