## Key commands in today's workshop


- kubectl version

- kubectl cluster-info

- kubectl get all 

- kubectl run monday26 --image=nmuta/python_experiment:one 

- kubeclt delete pod *podname*

- kubectl port-forward *podname* *port*

- kubectl create *myfile.yml*

- kubectl apply *myfile.yml*

- kubectl create -f myfile.yml --save-config

- kubectl apply -f myfile.yml

- kubeclt delete  -f myfile.yml ( deletes whatever was created by that yaml file)

- kubectl get deployments


* remember that "apply" is a "find or create" method and really the only thing you need to create local deployments 

- kubectl scale deployment *deployment name* --replicas=10

- kubectl scale -f myfile.yml --replicas=10

- kubectl delete pods --all






```
Kubernetes cheat sheet: 
https://kubernetes.io/docs/reference/kubectl/cheatsheet/
```







 






