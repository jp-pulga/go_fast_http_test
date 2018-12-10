# Performace result

```
$ wrk -t18 -c400 -d30s http://127.0.0.1:8080/
Running 30s test @ http://127.0.0.1:8080/
  18 threads and 400 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency   579.65us  609.13us  37.75ms   92.98%
    Req/Sec    39.45k     5.33k  114.39k    76.98%
  21231017 requests in 30.10s, 2.83GB read
Requests/sec: 705370.70
Transfer/sec:     96.20MB
```
