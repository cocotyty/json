###json###
just add style with json
```go
    json.MarshalWithStyle(something,json.UnderCaseStyle)
    json.UnmarshalWithStyle(data,something,json.UnderCaseStyle)
```
this lib just copy from https://golang.org/pkg/encoding/json/