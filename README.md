# .trunk

the repo that we'll create in customers' orgs, in which we launch workflows that run "trunk check" on repos in their org

this workflow invocation is what we want the webhook to do:

```
gh workflow run check-service.yaml -f client_payload="$(cat call.json)"
```
test repo
