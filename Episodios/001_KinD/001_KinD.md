# Criando um cluster local com KinD

Link do Episódio: 

- Instalando - https://kind.sigs.k8s.io/docs/user/quick-start/#installation
- Use o arquivo de conf de [exemplo](kind-conf.yaml).
- Criando o Cluster `kind create cluster --name supercluster --config kind-conf.yaml`
- Verificando seus clusters atuais `kind get clusters`
- Deletando clusters `kind delete cluster --name supercluster`
