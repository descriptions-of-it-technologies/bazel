# Bazel Commands.





## Sort this commands

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel build :container                                   |                                                                                                                          |
| bazel build :all-external-targets                        |                                                                                                                          |
| bazel clean                                              |                                                                                                                          |
| bazel run :tests                                         |                                                                                                                          |
| bazel build :tests                                       |                                                                                                                          |
| bazel test :tests                                        |                                                                                                                          |
|                                                          |                                                                                                                          |
|                                                          |                                                                                                                          |





## bazel build

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel build //:[targetName]                              |                                                                                                                          |
| bazel build //:[testTargetName]                          |                                                                                                                          |
| bazel build //...                                        |                                                                                                                          |
| bazel build //...:all                                    |                                                                                                                          |
|                                                          |                                                                                                                          |





## bazel run

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel run //:[targetName]                                |                                                                                                                          |
| bazel run //:[testTargetName]                            |                                                                                                                          |
|                                                          |                                                                                                                          |




## bazel test

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel test //:[testTargetName]                           |                                                                                                                          |
| bazel test //...                                         |                                                                                                                          |
|                                                          |                                                                                                                          |





## bazel clean

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel clean                                              |                                                                                                                          |
| bazel clean --expunge                                    |                                                                                                                          |
|                                                          |                                                                                                                          |





## bazel query

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
|                                                          |                                                                                                                          |

 `bazel query '//... except kind(.*test, //...)' | xargs bazel build`





## bazel cquery

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel cquery //...                                       | Show all targets.                                                                                                                         |
|                                                          |                                                                                                                          |





## bazel info

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel info                                               | To show information about bazel project. Must be run in a bazel workspace.                                                                                                                         |
| bazel info execution_root                                |                                                                                                                          |
|                                                          |                                                                                                                          |





## bazel fetch

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel fetch //...:all                                    |                                                                                                                          |
| bazel fetch //...                                        | To prefetch all dependencies, normally happens as part of bazel build.                                                                                                                         |
|                                                          |                                                                                                                          |



## bazel shutdown

| Key/Command                                              | Description                                                                                                              |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| bazel shutdown                                           | Shut down the workspace's bazel processes.                                                                                                                         |
|                                                          |                                                                                                                          |