# first-go-project
First steps with GoLang...
Following the official GoLang-Tour[https://tour.golang.org/].

## Setup your environment
1. Install Go
2. Set the GOPATH env: https://github.com/golang/go/wiki/SettingGOPATH
3. Setup your Go workspace structure, e.g.:
    ```
    src/
        github.com/gitflo1/first-go-project/
            .gitignore
            go.mod
            hello.go
            README.md
        <other-go-project>
            ...
            ...
    bin/
        first-go-project.exe
        other-go-project.exe
    ```
4. You can initialize a new Go project with the Go-CLI, e.g.: `go mod init github.com/gitflo1/first-go-project`
5. Build your project to create an .exe file: `go install github.com/gitflo1/first-go-project`
6. Run the .exe file: `first-go-project` (Just type it your shell, Assuming the `$GOPATH` variable is setup correctly)

[]: https://tour.golang.org/