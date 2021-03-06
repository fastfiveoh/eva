docs/eva_generate_cloudfront-response.md## eva generate cloudfront-response

Generate a cloudfront request event.

### Synopsis

Generate a cloudfront request event.

```
eva generate cloudfront-response [flags]
```

### Options

```
  -A, --auth string                 Authorization header
  -c, --command string              Pipe event(s) into specified shell command
  -d, --data string                 Data for body, or '-' for stdin.
  -h, --help                        help for cloudfront-response
  -H, --host string                 HTTP(s) host for event data.
  -l, --lambda string               Process event(s) with specified AWS Lambda ARN
  -e, --log-event string            Log process event(s) into file, or - for stdout
  -E, --log-event-response string   Log response event(s) into file, or - for stdout
  -X, --method string               HTTP Method (default "GET")
  -p, --path string                 HTTP(s) path or uri.
  -q, --quiet                       Do not print to stdout/stderr unless -e or -E is specified.
```

### Options inherited from parent commands

```
      --config string   config file (default is $HOME/.eva.yaml)
```

### SEE ALSO

* [eva generate](eva_generate.md)	 - Generate events for serverless functions.

###### Auto generated by spf13/cobra on 4-May-2018
