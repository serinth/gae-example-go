This repo hosts a tutorial on how to get started withi Google App Engine (GAE).

# Slides

Slides are using the [Golang Present tool](https://godoc.org/golang.org/x/tools/present) which can be installed into your GOPATH with:

```bash
go install golang.org/x/tools/cmd/present
```

Then to execute the slides:

```bash
cd slides
./present.sh
```

`present.sh` is a bash shorthand for executing the `main.slide` file with the present tool.

# App Engine Example

`app.go` is a simple web app from Google's examples in the flex environment available [here](https://github.com/GoogleCloudPlatform/golang-samples/tree/master/appengine_flexible/helloworld).

`app.yaml` is an example deployment of the service.