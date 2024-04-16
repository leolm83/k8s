# K8S

# GET PODS

## Listar os pods
kubectl get pods
 
## listar os pods e acompanhar
kubectl get pods --watch

## listar os pods formatado
kubectl get pods -o wide

## Criar pod baseado num arquivo yml

kubectl apply -f <caminho do arquivo>

## Deletar 

### apenas um pod usando o nome
kubectl delete pod <nome do pod>

### todos baseado em um arquivo
kubectl delete -f <caminho do arquivo>




## obter informacoes sobre o pod

kubectl describe pod <nome pod>

# executar comandos no pod
kubectl exec -it <nome container> -- bash
