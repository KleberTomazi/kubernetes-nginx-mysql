# Infrastructure and Cloud Computing
## Atividade Kubernetes - Aula 4

### -> Subir os POD's do NGINX e MySQL

``` kubectl apply -f service  ```

### -> Verificar se o NGINX subiu 

Acesse o seguinte endereço: 

``` 127.0.0.1 ```

### -> Verificar se o MySQL subiu

Execute a seguinte linha de comando:

``` kubectl run -it --rm --image=mysql:5.7 --restart=Never mysql-client -- mysql -h db-service -p Kl&ber@2013 ```

#### ! IMPORTANTE ! 

A atividade foi executada localmente através do Docker Desktop.
