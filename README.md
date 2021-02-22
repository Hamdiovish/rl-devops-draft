kubectl apply -f crd.yaml  
kubectl apply -f instance*.yaml  
kubectl get rl

kopf run op.py --verbose  