## This is test go mod on public repository

- use personal access token to communicate with https://github.com/makotechg/test-public

- go.mod
    - `go mod init  github.com/makotechg/test-public`
    - ```go.mod
        module github.com/makotechg/test-public

        go 1.16
        ```

- main.go
    - ```
        import (
        	"github.com/makotechg/test-public/subpkg"
        )
        ```

## how to change remote url
- `git remote set-url origin ${NEW_URL}`