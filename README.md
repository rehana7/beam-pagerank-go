# beam-pagerank-go
Calculating the page rank using go.

[Go Quickstart](https://beam.apache.org/get-started/quickstart-go/) 
[Beam programming-guide](https://beam.apache.org/documentation/programming-guide/)
[Reference: Dr.Case beam-parerank-go](https://github.com/denisecase/beam-pagerank-go)

## Check go version
```
go version
```
## Initialize module beam-pagerank-go
```
go mod init github.com/rehana7/beam-pagerank-go
```
## Get SDK for go
```
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
```
if any errors stating a package is required:
```
go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
```
## Build the executable 
By following the command, a new .exe executable file is created.
```
go build pagerank.go
```
## Run the executable
```
.\pagerank.exe --input <PATH_TO_INPUT_FILE> --output count.csv
```


