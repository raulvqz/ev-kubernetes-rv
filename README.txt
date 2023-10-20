Añadir en /hosts:
- 127.0.0.1 rvazquez-dominio.com

Comandos a ejecutar para que funcine:
- minikube start
- minikube addons enable ingress
- minikube addons enable ingress-dns
- kubectl create secret generic my-secret --from-literal=POSTGRES_USER=odoo --from-literal=POSTGRES_PASSWORD=odoo --from-literal=POSTGRES_DB=postgres
- kubectl apply -f .
- minikube tunnel

Acceder a tu dominio:
- rvazquez-dominio.com
