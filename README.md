# Bazel.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Bazel Commands.](bazel-commands.md)
* [Remote Build Execution API.](remote-build-execution-api.md)
* [Pros.](#pros)
* [Cons.](#cons)
* [Help](#help)





## About.





## Documentation.





## Pros.
* Correct - newer need to "clean" or wonder if build outputs are up-to-date. 
* Fast - provide fast build execution.
  * Parallelism - execute on multiple locale or remote CPUs
  * Incremental - don't re-build everything from scratch
* Deterministic - the output depends entirely on the input(predictability, caching)
* Composable - allows reuse of existing build rules and creating new ones by combining them.
* Universal - Builds Android, iOS, web, backends, cloud services, and more...
* Multi-process - Isolation, allow more tool runtimes, defense against mem leaks.
* Reproducible build and test.
* Cloud accelerated.
* OSS solution.
* Google Cloud Build.
* D.R.Y Only retest when necessary.
* Bazel's build graph optimizes new work. 
  * Independent piece of code will be builds in parallel.
  * Reuse still-valid build/test results.
* Execute tests in parallel.
* Scalable.
* Bazel's cache elements re-work. 
  * Cloud cache.
* Bazel builds ~all the things.
* Use all cores to build and test.
* 





## Cons.
* Code analysis tool.
* More config tool to maintain.





## Google Cloud Build.
* Google Results Store
* Build History filters
* Google RBE Alpha



##
* Target Unit.
  * Rule.
* Sandbox





## Conferences.
* [DevoxxUA 2018: Build and test your code faster with Bazel, the cloud-accelerated build system.](https://www.youtube.com/watch?v=QFqcKT6sGoc)
* [How to successfully migrate to Bazel from Maven or Gradle. (Natan Silnitsky, Israel)](https://www.youtube.com/watch?v=2UOFm-Cc_cU)
* []()



## Help.
