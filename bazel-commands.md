# Bazel Commands.

## General

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel build //...                                        |                                                                                                                          |
| bazel build //...:all                                    |                                                                                                                          |
| bazel build //:targetName                                |                                                                                                                          |
| bazel clean                                              |                                                                                                                          |
| bazel clean --expunge                                    |                                                                                                                          |
|                                                          |                                                                                                                          |

 `bazel query '//... except kind(.*test, //...)' | xargs bazel build`
 `bazel-3.5.0 query '//... except kind(.*test, //...)' | xargs bazel-3.5.0 build`
 `bazel-3.5.0 query '//...:all except kind(.*test, //...:all)' | xargs bazel-3.5.0 build //...:all`
 
 `bazel`
 `bazel-2.0.0`
 `bazel-3.3.0`
 `bazel-3.5.0`
 `bazel-3.5.1`
 `bazel-3.7.1`