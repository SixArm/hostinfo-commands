# hostinfo commands for macOS

Commands:

* [`hostinfo-loadavg`](hostinfo-loadavg): What is the processor load average number?
* [`hostinfo-loadavg-logical`](hostinfo-loadavg-logical): What is the processor load average per logical processor?
* [`hostinfo-loadavg-physical`](hostinfo-loadavg-logical): What is the processor load average per physical processor?
* [`hostinfo-mach-factor`](hostinfo-mach-factor): What is the processor mach factor number?
* [`hostinfo-mach-factor-logical`](hostinfo-mach-factor-logical): What is the processor mach factor per logical processor?
* [`hostinfo-mach-factor-physical`](hostinfo-mach-factor-physical): What is the processor mach factor per physical processor?
* [`hostinfo-primary-memory-available`](hostinfo-primary-memory-available): How much primary memory is available?
* [`hostinfo-processor-type`](hostinfo-processor-type): What is the processor type?
* [`hostinfo-processors-logical`](hostinfo-processors-logical): How many processors are logically available?
* [`hostinfo-processors-physical`](hostinfo-processors-physical): How many processors are physically available?

Examples:

    $ hostinfo-loadavg
    1.20

    $ hostinfo-mach-factor
    2.40

    $ hostinfo-primary-memory-available
    16.00 gigabytes

    $ hostinfo-processor-type
    x86_64h (Intel x86-64h Haswell)

    $ hostinfo-processors-logical
    4

    $ hostinfo-processors-physical
    2


## Tracking

  * Package: hostinfo-commands
  * Version: 1.0.0
  * Created: 2017-11-01
  * Updated: 2017-11-02
  * License: GPL
  * Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)

