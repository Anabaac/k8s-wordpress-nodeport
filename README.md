# Exemplo Deploy WordPress e MySQL

Exemplo de um Deployment e Service do WordPress e MySQL. O Service do WordPress utiliza NodePort não estabelecida.

Para iniciar o MySQL:

    kubectl apply -f mysql.yaml

 Para iniciar o WordPress:

    kubectl apply -f wordpress.yaml

Se estiver utilizando Minikube, para acessar:

    minikube service wordpress --url
