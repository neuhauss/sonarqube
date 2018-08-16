# k8s-sonarqube
SonarQube for Kubernetes.


kubectl create secret generic postgres-pwd --from-literal=password=senha



$ kubectl create -f sonar-pv-postgres.yaml     
$ kubectl create -f sonar-pvc-postgres.yaml  
$ kubectl create -f sonar-postgres-deployment.yaml  
$ kubectl create -f sonarqube-deployment.yaml
$ kubectl create -f sonarqube-service.yaml
$ kubectl create -f sonar-postgres-service.yaml 
