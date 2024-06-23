# Budibase - Library Management App (Javascript code to implement login feature)

```cmd

const data = $("New Data Provider.Rows").filter((value) => {
  return value.Username === $("New Form.Fields.Username") && value.Password === $("New Form.Fields.Password")
})

if(data[0] == undefined){
  return "/error"
} else {
  return "/dashboard/" + data[0]._id
}


```
