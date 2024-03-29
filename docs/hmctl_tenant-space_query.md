## hmctl tenant-space query

Gets a list of all Tenant Spaces.

```
hmctl tenant-space query [flags]
```

### Options

```
      --authorization string      Access token for authorization header.
      --display-name string       Filter by display-name.
      --filter string             Filter by expression language.
  -h, --help                      help for query
      --id string                 Filter by id.
      --limit int32               Limit the number of results returned.
      --name string               Filter by name.
      --offset int32              Offset for results.
      --sort string               Filter by sort.
      --tenant-id string          Filter by tenant-id.
      --x-correlation-id string   Add correlation id to header.
      --x-request-id string       Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl tenant-space](hmctl_tenant-space.md)	 - Perform operations on tenant-space resources

###### Auto generated by spf13/cobra on 16-Feb-2023
