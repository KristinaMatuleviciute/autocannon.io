---
layout: main.html
---

## Install

```
npm i autocannon -g
```


## Command Line

```
Usage: autocannon [opts] URL

Available options:

  -c/--connections NUM  The number of concurrent connections to use
  -p/--pipelining NUM   The number of pipelined requests to use
  -d/--duration SEC     The number of seconds to run the autocannnon
  -m/--method METHOD    The http method to use
  -b/--body FILE        The body of the request
  -h/--headers K=V      The request headers
  -j/--json             Print the output as json
  -l/--latency          Print all the latency data
  -h/--help             Print this menu
```


[node-gyp]: https://github.com/nodejs/node-gyp#installation
[wrk]: https://github.com/wg/wrk
[wrk2]: https://github.com/giltene/wrk2
