# GORM Sqlite Driver

Fork with `"modernc.org/sqlite"` (works with `CGO_ENABLED=0`)

## USAGE

```go
import (
  sqlite "github.com/aceberg/gorm-sqlite"
  
  "gorm.io/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

