# xrprof 0.2.0

* `libelf` is now required.

* Support for profiling R processes running in Docker containers. (#6)

* Support for profiling R when built without `libR.so`. (#7)

* Fixes a memory leak.

# xrprof 0.1

* Initial public release. `xrprof` is an external sampling profiler for R on
  Linux.