Steps to get this containerized WordPress up & running:

1 - Create directory /mnt/pv01 and /mnt/pv02 on each K8s node

1 - Create namespace "wp" (kubectl apply -f wordpress-namespace.yaml)

2 - Deploy WordPress (kubectl apply -k ./ -n wp)
