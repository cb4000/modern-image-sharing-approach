# modern-image-sharing-approach
## To discover more about the best practices for rolling out microervice architectures in kubernetes.


### Cloud deployment: requires eksctl helm and istio
e.g.: 
eksctl create cluster --name udacity-test2 --version 1.14 --region us-east-2 --fargate
th

kubectl cluster-info

curl -L https://git.io/getLatestIstio | sh -
cd istio-1.*
kubectl create -f install/kubernetes/helm/helm-service-account.yaml
helm init --service-account tiller

kubectl create secret generic  env-secret --from-file=POSTGRESS_USERNAME=/home/charles/postgres-user.txt --from-file=POSTGRESS_PASSWORD=/home/charles/postgres-pw.txt
