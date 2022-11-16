## hmctl placement-group create

Creates a Placement Group.

```
hmctl placement-group create [flags]
```

### Options

```
      --authorization string       Access token for authorization header.
      --availability-zone string   The name of the Availability Zone. (Required)
      --display-name string        The display name of the resource.
  -h, --help                       help for create
      --name string                The name of the resource, supplied by the user at creation, and used in the URI path of a resource. (Required)
      --region string              The name of the Region. (Required)
      --storage-service string     The name of the Storage Service. (Required)
  -t, --tenant string              The name of the Tenant. (Required)
  -s, --tenant-space string        The name of the Tenant Space. (Required)
      --x-correlation-id string    Add correlation id to header.
      --x-request-id string        Add operation idempotence id to header.
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl placement-group](hmctl_placement-group.md)	 - Perform operations on placement-group resources

###### Auto generated by spf13/cobra on 10-Nov-2022