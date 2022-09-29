# terraform-hashi-cluster-digitalocean

# 🚀 A Hashicorp (Vault, Consul, Nomad) cluster on Digital Ocean 🚀

https://github.com/coding-to-music/terraform-hashi-cluster-digitalocean

From / By https://github.com/brucellino/terraform-hashi-cluster-digitalocean

## Digitalocean Droplet Prices

https://github.com/andrewsomething/do-api-slugs

https://slugs.do-api.dev

```
# https://slugs.do-api.dev/

# s-1vcpu-512mb-10gb  $4    10GB
# s-1vcpu-1gb         $6    25GB
# s-1vcpu-2gb         $12   50GB
# s-2vcpu-2gb         $18   60GB
# s-2vcpu-4gb         $24   80GB
# s-4vcpu-8gb         $48   160GB
```

## Environment variables:

```java

```

## user interfaces:

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/terraform-hashi-cluster-digitalocean.git
git push -u origin main
```

# terraform-hashi-cluster-digitalocean

A Hashicorp (Vault, Consul, Nomad) cluster on Digital Ocean

## Attempt to run

```
terraform init
```

```
Upgrading modules...
Downloading registry.terraform.io/brucellino/consul/digitalocean 1.0.4 for consul...
- consul in .terraform/modules/consul
Downloading registry.terraform.io/brucellino/vpc/digitalocean 1.0.0 for vpc...
- vpc in .terraform/modules/vpc

Initializing the backend...
╷
│ Error: Failed to get existing workspaces: Get "http://consul.service.consul:8500/v1/kv/terraform/digitalocean/hashi-cluster-env:?keys=&separator=%2F": dial tcp: lookup consul.service.consul on 127.0.0.53:53: no such host
│
│
```
