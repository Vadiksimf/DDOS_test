# DDOS_test

## Linux simple crash test

n — amount of requests, с — amount of simultaneous requests.
```
ab -n 10 -c 10 https://site.com
```

```
siege -d -c10 -t10S https://site.com
```
