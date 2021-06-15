# Criando um cluster local com KinD

- Instalando - https://kind.sigs.k8s.io/docs/user/quick-start/#installation
- Use o arquivo de conf de [exemplo](https://github.com/getupcloud/kubedrops/blob/main/Episodios/001_KinD/kind-conf.yaml "exemplo").
- Criando o Cluster `kind create cluster --name supercluster --config kind-conf.yaml`
- Verificando seus clusters atuais `kind get clusters`
- Deletando clusters `kind delete cluster --name supercluster`
