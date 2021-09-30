# helloworld

```sh
bazel run //:gazelle
bazel run //:gazelle -- update-repos -from_file=go.mod
bazel run //greeter_server:greeter_server
bazel run //greeter_client:greeter_client
```
