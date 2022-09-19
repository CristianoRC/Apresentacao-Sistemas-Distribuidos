---
theme: "night"
transition: "slide"
title: "Sistemas Distribuídos"
enableMenu: false
enableSearch: false
enableChalkboard: false
---

### Distributed Systems

![-](https://inelpandzic.com/wp-content/uploads/2021/04/blockchain-3508589_1280-min.png)

---

### Objetivos

- Dar uma introdução sobre Sistemas distribuídos
- Dar uma introdução sobre Microsserviços
- Conceitos relacionados que sempre aparecem por aí
- Tirar as dúvias

---

### O que é?

---

#### Processamento em mais de um computador

---

A distributed system is a collection of independent computers that appears to users as a single computer. - ANDREW S. TANENBAUM

---

### Obrigado!

---

- Não compartilha memória(entre os serviços)
- Podem ser processados em paralelo
- Baixo acoplamento(um não depende obrigatoriamente do outro)
- Falham de forma independente(se 1 quebrar segue o baile)

---

### Quando usar?

Escala de Time(menos comum)

---

### Quando usar?

Escala de de Sistema

---

### Vertical vs. Horizontal

---

### Todo o sistema pode ser Distribuído?

---

### Caso de um Moniolito

---

### Caso de um Moniolito

- Compartilha memória ou disco

---

### Caso de um Moniolito

- Compartilha memória ou disco
- Session/Files(local)

---

#### Caso de um Moniolito - Como Escalar

![-](./Images/monolito.png){width=50%}

---

#### Caso de um Moniolito - Como Escalar

![-](./Images/monolito-2.png){width=70%}

---

#### Caso de um Moniolito - Como Escalar

![-](./Images/monolito-3.png){width=70%}

---

#### Caso de um Moniolito - Como Escalar

![-](./Images/monolito-4.png){width=50%}

---

### Load Balancer

![-](./Images/loadBalancer.png){width=40%}

---

#### Caso de um Moniolito - Escalam?

<iframe width="560" height="315" src="https://www.youtube.com/embed/BiA_TfW76mc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

#### Caso de um Moniolito - StackOverFlow

<iframe width="560" height="315" src="https://www.youtube.com/embed/7LEWQZim5O4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

### Tirando Monolitos Só existem Microsserviços?

---

### Muito mais que Microsserviços

![-](./Images/grandesServicos.png){width=53%}

---

### API Gatway

![-](./Images/apiGatway.png){width=53%}

---

#### API Gatway vs. Management

![-](./Images/apiManagement.png){width=63%}

---

### Service Mesh

![-](./Images/servicemesh.png)

---

### Service Discovery

![-](./Images/serviceDiscovery.png){width=90%}

---

### Microsserviços

---

#### Microsserviços

![-](https://wac-cdn.atlassian.com/dam/jcr:d76e535a-b5ad-473a-b697-26dab8b73c18/microservice_architecture_v2.png?cdnVersion=531){ width=65% }

---

### Microsserviços - Princípios

1. Alta Coesão
1. Autônomos
1. Resiliência
1. Observável
1. Centrado no domínio do negócio
1. Automatização

---

### Microsserviços - Comunicação

![-](https://cdn.solace.com/wp-content/uploads/2019/11/Orchestration-VS-Choreography.png)

---

### Orquestração

![-](https://cdn.solace.com/wp-content/uploads/2019/11/Orchestration-600x600.png){ width=60% }

---

### Coreografia

![-](https://cdn.solace.com/wp-content/uploads/2019/11/Choreography-600x600.png){ width=60% }

---

### Event-Driven

![-](https://miro.medium.com/max/1400/1*whx8kk4B_WzF3Wz6ifc24g.png)

---

### Distributed tracing

![-](https://miro.medium.com/max/1191/1*O4Kb0ToSpFXLxEF4xKPWXA.png)

---

### Dúvidas?

![alt](https://media3.giphy.com/media/3o6MbudLhIoFwrkTQY/giphy.gif?cid=790b76117789c6161150915091725a365bdeac4e06fd01cd&rid=giphy.gif&ct=g){ width=90% }
