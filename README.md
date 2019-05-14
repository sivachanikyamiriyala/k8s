# k8s
1.To see the list of nodes in k8s cluster
   kubectl get nodes
2.To see the list of pods in k8s cluster
  kubectl get pods
3.To see the list of pods in wide 
  kubectl get pods -o wide
4.To start nginx as a deployment in k8s cluster
  kubectl run --image nginx webserver --port=80 --hostport=9090
5.To start tomcat in k8s cluster and perform port mapping 
  kubectl run --image tomcat appserver --port=8080 --hostport=9091 
6.To start mysql in k8s
  kubectl run --image mysql:5 mydb --env MYSQL_ROOT_PASSWORD=admin
7.To open in interactive mode of mydb
  kubectl exec -it mydb bash
8.To see the logs
  kubectl log -f podname
9.To delete a pod
  kubectl delete service_name
  
  
