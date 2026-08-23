# FRPC Kubernetes system stack for Wodby

FRPC supplies tunneling infrastructure for Wodby cluster networking
configurations that require an FRP client.

This repository defines the Wodby stack manifests and default service
composition for FRPC.

<!-- wodby:generated:start -->

## Stack contract

- [FRPC stack on Wodby](https://wodby.com/stacks/frpc)
- [Wodby Kubernetes platform](https://wodby.com)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## System service definitions

- [FRPC system service](https://github.com/wodby/service-frpc)

## What's included

| Component / service | Default configuration |
| --- | --- |
| FRPC<br>`frpc` | required; enabled by default |

System services are enabled or disabled according to the cluster provider and
infrastructure configuration.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
