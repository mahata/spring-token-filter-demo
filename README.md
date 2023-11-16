# PoC for an API-token based app

```
$ curl http://localhost:18081/demo -H "Authorization: oktoken"
Yo
$ curl http://localhost:18081/demo -H "Authorization: badtoken"
```
