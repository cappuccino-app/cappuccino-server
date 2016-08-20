## ***/download/*** Entry Point

| Information | Value |
| ----------- |:-------------:|
| URL      | `/download/`        |
| Method   |           GET      |
| Url Params | ***command(STRING)***, ***currentDir(STRING)***      |

### Success Response
Try to visit the following url with your browser and you should see a `download/open file window` prompting:

    http://localhost:8000/download/?command=dw mattia&currentDir=/


### Error Response
coming soon ...

### Sample Call

```javascript
$http.get("/command/", {
        params: {
            "command": "dw mattia",
            "currentDir": "/",
        }
    }).success(callback).error(callback); |
```

or by using `curl` utility:
coming soon ...