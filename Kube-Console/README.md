#Apply kube conspole
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.0.0-beta1/aio/deploy/recommended.yaml

#Access to kube drashboard
http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#/login

##apply rule
kubectl apply -f dashboard-adminuser.yaml 

##get secret
kubectl -n kubernetes-dashboard get secret

##more secret
kubectl -n kubernetes-dashboard describe secret admin-user-token-9vpkp