# Docker Compose

## Quick Start

```bash
alias fig="docker run --name compose --rm \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v $PWD:/src \
    cedvan/compose:latest"
```