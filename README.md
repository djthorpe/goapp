# goapp

The repository is a template for a Go application. In order to
create a new application from it, follow the following steps.

You'll want to download the Go compiler and libraries from
`https://golang.org/dl/` first.

Navigate to https://github.com/djthorpe/goapp and click on
"Use this template". It will then allow you to name your 
repository.


Clone the repository to your local computer and edit it.
You'll want to type the following command to update the
`go.mod` file, be sure to change anything starting with __My__:

```bash
cd MyRepository
go mod init github.com/MyUsername/MyRepository
```

The following folders within the repository should be used:

  * `cmd/` for command-line binaries that need to be built;
  * `pkg/` for packages which form part of any system.

You include packages into your binaries as per the example
in this package (which you can delete).

## Using a Makefile

The `Makefile` example assumes you are using GNU Make in
order to run tests and compile command-line binaries:

  * `make` with no arguments builds each command and puts
    the binary into the `build` folder;
  * `make test` will run tests on the packages;
  * `make clean` will return the repository to clean state
    with no artifacts.

You don't need to use a Makefile as part of your toolchain,
however.



