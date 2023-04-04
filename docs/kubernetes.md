# Kubernetes

## Creating a k3d cluster

```bash
k3d cluster create
```

## Deploy a httpbin

```bash linenums="1"
kubectl create namespace example

kubectl create deployment httpbin \
  --image silviosilva/httpbin \
  --replicas 1
```

``` yaml
theme:
  features:
    - content.code.annotate # (2)
```

1.  I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

2.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.
