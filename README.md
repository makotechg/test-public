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

## how to use remote url command
- change
    - `git remote set-url ${ORIGINAL_REMOTE_REPO_NAME} ${NEW_URL}`
- add
    - `git remote add ${ORIGINAL_REMOTE_REPO_NAME} ${NEW_URL}`