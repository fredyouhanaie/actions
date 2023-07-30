# Erlang app docker action

This action runs an erlang/rebar3 command inside a docker container.

## Inputs

### `command`

The `rebar3` command to run.

## Outputs

No output variables.

## Example usage

```
uses: fredyouhanaie/hello-world-docker-action/actions/erlang@v2
with:
  command: 'eunit'
```

---
