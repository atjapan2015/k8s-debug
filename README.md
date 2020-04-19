
step1:create docker images
```
docker build -t atjapan2015/studyk8s:v1 .
```

step2:deploy to kubernetes cluster
```
kubectl apply -f greeting.yaml
```
