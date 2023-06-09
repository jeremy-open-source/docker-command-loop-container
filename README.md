# Docker command loop container

Deprecated, replaced with https://gitlab.com/jeremy-open-source/docker-containers/-/tree/master/command-loop

I needed a simple container to run a few commands continuously in a loop like nmap and curl, so I created this quickly

## Docker Usage
```
docker run --rm registry.gitlab.com/jeremy-open-source/docker-command-loop-container:latest nmap -sP 1.2.3.4/32

```

## Development Usage

To run nmap against a single host:
```
docker-compose run --rm app nmap -sP 1.2.3.4/32
```
