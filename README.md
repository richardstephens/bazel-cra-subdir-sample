This repo contains a copy of the Bazel create-react-app sample
from [the rules_nodejs repo](https://github.com/bazelbuild/rules_nodejs/tree/stable/examples/create-react-app),
but demonstrating how to build the app from a subdirectory

You can build this with

    bazel build //webapp:build
