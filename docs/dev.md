# Development

Source code is located in `src/github.com/cppforlife/turbulence`. Use `manifests/api.yml` and `manifests/dummy.yml` to deploy API server and agents to BOSH Lite.

Run `./src/github.com/cppforlife/turbunlence/bin/test` for unit tests.

## Dependencies

Run `./update-deps` to update `github.com/cppforlife/turbulence` package dependencies. `deps.txt` will be updated with Git SHAs for each dependency.

## Planned tasks

- lock up whole machine
- remount disk as readonly
- corrupt disks
- pause a process
- restrict X% bandw

https://www.kernel.org/doc/Documentation/sysrq.txt might be useful...
http://blog.hut8labs.com/gorillas-before-monkeys.html
http://techblog.netflix.com/2011/04/lessons-netflix-learned-from-aws-outage.html
