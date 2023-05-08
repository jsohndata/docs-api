# Fetch Headers Detail

```
fetch('https://notiempo.lol/api/plants', {
  method: 'GET',
  headers: {
    'Content-Type': 'application/json',
    'Accept': 'application/json',
    'Access-Control-Allow-Origin': '*'}      
  })
  .then(res => res.json())
  .then(data => setData(data))
  .catch(console.err)    
```

`Accept`
This indicates the type of data that the client (i.e., your application) is willing to accept in the response from the server. In this case, the client is indicating that it will accept JSON data (`application/json`). This header is important because it helps the server know what format to send the response data in.

`Access-Control-Allow-Origin` 
This is a CORS (Cross-Origin Resource Sharing) header that indicates which origins are allowed to access the requested resource. In this case, the '*' value indicates that any origin is allowed to access the resource. This header is important because it helps prevent cross-site scripting attacks by limiting which websites are allowed to access the server's resources.