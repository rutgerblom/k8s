Steps to get this containerized WordPress up & running:

1 - Create namespace "wp" (kubectl apply -f wordpress-namespace.yaml)

2 - Deploy WordPress (kubectl apply -k ./ -n wp)
