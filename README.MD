
<h2> Servidor Redis </h2>

- Deployment;
- Service (ClusterIP);
- Secret;

<h2> Aplicação </h2>

- Deployment;
- Service (NodePort);
- ConfigMap;
- Secret;

<br>

<p align="center">
    <img src="img/ClusterAll.png" alt="Cluster"/>
    <br>
    <span>Recursos do Cluster</span>
</p>
<br>
<p align="center">
    <img src="img/grk1.png" alt="app-grk1"/>
    <br>
    <span>Acesso ao grk-app pelo nó/vm do minikube</span>
</p>
<p align="center">
    <img src="img/grk2.png" alt="app-grk1"/>
    <br>
    <span>Em produção o Ingress Controller é o recurso mais indicado para expor rotas HTTP e HTTPS para serviços dentro do Cluster, porém, para fins de estudo foi utilizado o NodePort.</span> 
</p>