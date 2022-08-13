This project is part of the simple webapp series. In this project, I have used kubernetes to create contianers in the Pod and used NodePort service to expose my webapp on 32000 port.

Run this command to create deployment containing required containers

Kubectl apply -f simpleapp.yml

This command will create NodePort service to expose application on 32000

kubectl apply -f appsvc.yml
