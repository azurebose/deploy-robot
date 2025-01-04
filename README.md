# deploy-robot
Download the file in to your local device and modify as per the requirments.

Reference:
https://www.youtube.com/watch?v=tE61nVUMghU

kubectl apply -f deploy-robot.yml

kubectl get serviceAccounts

kubectl get secrets

kubectl get serviceAccounts deploy-robot  -n default -o=jsonpath={.secrets[*].name}

kubectl get secret deploy-robot-secret -n default -o json

