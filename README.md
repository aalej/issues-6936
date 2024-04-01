# Repro for issue 6936

## Steps to reproduce

1. Run `firebase emulators:start --project demo-project`
1. Open a new terminal, run `curl localhost:8888/baz`
   - Outputs the ff:

```json
{
  "some_key": "some_value"
}
```
