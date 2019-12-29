Steps to get this containerized WordPress up running:

1 - Copy the yaml files to a directory on the K8s master node

2 - Create directory /mnt/pv01 and /mnt/pv02 on each K8s worker node

3 - Create namespace "wp" (kubectl apply -f namespace.yaml)

4 - Deploy WordPress (kubectl apply -k ./ -n wp)
