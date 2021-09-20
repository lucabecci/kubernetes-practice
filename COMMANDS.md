# KUBECTL commands

```md
kubectl get nodes

kubectl config get-contexts 

kubectl get ns

kubectl -n kube-system get pods

kubectl -n kube-system delete pod <NAME OF THE POD>

kubectl apply -f <NAME OF THE MANIFEST.YAML>

kubectl get pods

kubectl get pod <METADATA TAG NAME OF THE POD>

kubectl exec -it <METADATA TAG NAME OF THE POD> -- sh

kubectl delete pod <NAME OF THE POD>

kubectl get pod <METADATA TAG NAME OF THE POD> -o yaml

kubectl delete -f <NAME OF THE MANIFEST.YAML>
```