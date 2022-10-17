# Serverless config

In the terminal, run:

```
sls configure credentials --provider aws --key <AWS KEY> --secret <AWS SECRET> -o
```

The `-o` overrides the existing `[default]` pair in the `~/.aws/credentials` file.
