# kotrcli
kotr is api client for KING OF TIME My Recorder.

# Usage
```go
package main

import (
	"fmt"
	"github.com/kotrcli/kotrcli"
)

func main() {
  token := "YOURTOKEN"
  userToken := "YOURUSERTOKEN"
  result := kotrcli.Dakoku(kotrcli.SYUKKIN, token, userToken)
  fmt.Println(result)
}
```
