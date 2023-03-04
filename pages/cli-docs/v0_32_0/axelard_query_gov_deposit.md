## axelard query gov deposit

Query details of a deposit

### Synopsis

Query details for a single proposal deposit on a proposal by its identifier.

Example:

```bash
$ <appd> query gov deposit 1 cosmos1skjwj5whet0lpe65qaq4rpq03hjxlwd9nf39lk
```

```
axelard query gov deposit [proposal-id] [depositer-addr] [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for deposit
      --node string     `<host>:<port>` to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string     The network chain ID (default "axelar")
      --home string         directory for config and data (default "$HOME/.axelar")
      --log_format string   The logging format (json|plain) (default "plain")
      --log_level string    The logging level (trace|debug|info|warn|error|fatal|panic) (default "info")
      --trace               print out full stack trace on errors
```

### SEE ALSO

- [axelard query gov](/cli-docs/v0_32_0/axelard_query_gov) - Querying commands for the governance module