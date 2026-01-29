kubectl get pods       #short cut kubectl get po
kubectl get services    #kubectl get svc
kubectl get nodes        #kubectl get no
kubectl get deployments  #short cut kubectl get deploy
kubectl get namespaces   #short cut kubectl get ns
kubectl get replicasets  #short cut kubectl get rs
kubectl get configmaps   #short cut kubectl get cm
kubectl get secrets      #short cut kubectl get se
kubectl get all          #get all resources in the default namespace
kubectl describe pod <pod-name>
kubectl get config # list all contexts #kubectl config get-contexts
cd spec:
kubectl get pods -o wide
kubectl get pods -o yaml
kubectl apply -f Deployment/web-annot-strategy.yaml //file name web-annot-strategy
kubectl delete -f Deployment/web-annot-strategy.yaml
kubectl rollout status deployment/web-annot-strategy
kubectl apply -f daemonset/web-daemonset.yaml


# when daemon comes in picture we use daemonset instead of deployment why simple can you explain

