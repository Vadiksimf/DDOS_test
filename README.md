# DDOS_test

## Linux simple crash test

n — amount of requests, с — amount of simultaneous requests.
```
ab -n 10 -c 10 https://staff.fusion-team.com/calendar
```

```
siege -d -c10 -t10S https://staff.fusion-team.com
```
