# demo-kubernetes-gcp-docker-voting-app
Pod and service creation commands:
for i in voting-app-pod.yml voting-app-service.yml redis-pod.yml redis-service.yml postgres-pod.yml postgres-service.yml result-app-pod.yml result-app-service.yml worker-app-pod.yml;do kubectl create -f $i;done

#check pods
kubectl get pods

#check services
kubectl get services
