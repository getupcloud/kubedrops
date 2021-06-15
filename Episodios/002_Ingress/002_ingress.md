# Expondo aplicações locais com Ingress no KinD

Link do Episódio: 

- Crie um cluster como mostramos no episódio [001](../001_KinD/001_KinD.md)
- Crie os componentes mandatórios do Nginx Ingress
  `kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/kind/deploy.yaml` 
- Verifique se todos os componentes já estão no ar: `kubectl -n ingress-nginx get all` 
- Crie um namespace para a aplicação demo:
  `kubectl create ns demo`
- Crie a aplicação demo com o arquivo [demo.yaml](demo.yaml):
  `kubectl -n demo apply -f demo.yaml`
- Veja o texto em seu navegador: http://localhost/foo
- 