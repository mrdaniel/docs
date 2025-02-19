---
id: keto-relation-tuple-create
title: keto relation-tuple create
description: keto relation-tuple create Create relationships from JSON files
---

<!--
This file is auto-generated.

To improve this file please make your change against the appropriate "./cmd/*.go" file.
-->
## keto relation-tuple create

Create relationships from JSON files

### Synopsis

Create relationships from JSON files.
A directory will be traversed and all relationships will be created.
Pass the special filename `-` to read from STD_IN.

```
keto relation-tuple create <relationships.json> [<relationships-dir>] [flags]
```

### Options

```
      --authority string                      Set the authority header for the remote gRPC server.
      --format string                         Set the output format. One of table, json, yaml, json-pretty, and jsonpath. (default "default")
  -h, --help                                  help for create
      --insecure-disable-transport-security   Disables transport security. Do not use this in production.
      --insecure-skip-hostname-verification   Disables hostname verification. Do not use this in production.
  -q, --quiet                                 Be quiet with output printing.
      --read-remote string                    Remote address of the read API endpoint. (default "127.0.0.1:4466")
      --write-remote string                   Remote address of the write API endpoint. (default "127.0.0.1:4467")
```

### Options inherited from parent commands

```
  -c, --config strings   Config files to load, overwriting in the order specified. (default [/home/runner/keto.yml])
```

### SEE ALSO

* [keto relation-tuple](keto-relation-tuple)	 - Read and manipulate relationships

