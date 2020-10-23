## Key commands in today's workshop


- kubectl version

- kubectl cluster-info

- kubectl get all 

- kubectl run mypod6 --image=nmuta/python_experiment:latest 

- kubeclt delete pod <podname>

- kubectl port-forward <podname> <port>

- kubectl create <myfile.yml or resource>

- kubectl apply <myfile.yml or resource>

- kubectl create -f myfile.yml --save-config

- kubectl apply -f myfile.yml


* remember that "apply" is a "find or create" method and really the only thing you need to create local deployments 

- kubectl scale deployment <deployment name> --replicas=10

- kubectl scale -f myfile.yml --replicas=10






 






