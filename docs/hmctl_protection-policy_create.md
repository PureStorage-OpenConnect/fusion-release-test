## hmctl protection-policy create

Creates a Protection Policy.

```
hmctl protection-policy create [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
      --display-name string       The display name of the resource.
  -h, --help                      help for create
      --local-retention string    Retention duration (in ISO 8601 format) for periodic snapshots. (Required)
      --local-rpo string          RPO duration (in ISO 8601 format) for periodic snapshots. (Required)
      --name string               The name of the resource, supplied by the user at creation, and used in the URI path of a resource. (Required)
      --x-correlation-id string   Add correlation id to header.
      --x-request-id string       Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl protection-policy](hmctl_protection-policy.md)	 - Perform operations on protection-policy resources

###### Auto generated by spf13/cobra on 17-Nov-2022