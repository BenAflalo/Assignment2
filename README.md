# Assignment2
second home test assignment

before you start you will need to have docker installed.
to start you need to install Kubernetes, go to this page: https://minikube.sigs.k8s.io/docs/start/
choose the OS you need and it will give you a command line to intall it in the terminal.
After it is installed use the command line "minikube start" to start your cluster.
before you continue create a diractory named "openLdap" and download the files "openldap.yaml" and "php.yaml" there.
Now to start working create a namespace "kubectl create namespace openldap"
then use this command line with this command line "kubectl create -f openldap.yaml"
and then use this command line for the other file "kubectl create -f php.yaml"
then use "minibuke tunnel"
now go to your browser and go to this link: https://localhost:9943
then log in with those credentials
User: cn=admin,dc=mydomain
Password: mypassword
