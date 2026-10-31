# flow-registry

The default registry for [Flow](https://github.com/oOBoomberOo/flow-lang).

`index.json` lists every package and its versions; each version points at a
directory under `packages/<name>/<version>` containing a `flow.json` and `src/`.

```
index.json
packages/
  flow-time/1.2.0/{flow.json,src/format.flow}
```

Point Flow at a different registry with `--registry`, a project `flow.json`
`"registry"` field, `~/.config/flow/config.json`, or `$FLOW_REGISTRY`.
