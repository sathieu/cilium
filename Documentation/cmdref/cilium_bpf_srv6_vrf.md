<!-- This file was autogenerated via cilium cmdref, do not edit manually-->

## cilium bpf srv6 vrf

List SRv6 VRF mappings

### Synopsis

List SRv6 VRF mappings.

Note that for Linux kernel versions between 4.11 and 4.15 inclusive, the native
LPM map type used for implementing this feature does not provide the ability to
walk / dump the entries, so on these kernel versions this tool will never
return any entries, even if entries exist in the map. 

```
cilium bpf srv6 vrf [flags]
```

### Options

```
  -h, --help            help for vrf
  -o, --output string   json| yaml| jsonpath='{}'
```

### Options inherited from parent commands

```
      --config string   Config file (default is $HOME/.cilium.yaml)
  -D, --debug           Enable debug messages
  -H, --host string     URI to server-side API
```

### SEE ALSO

* [cilium bpf srv6](cilium_bpf_srv6.md)	 - Manage the SRv6 routing rules

