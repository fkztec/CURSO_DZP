# DO ZERO AO DEPLOY #

- APRENDA A FAZER DEPLOY DE APLICAÇÕES NO KUBERNETES

# EMENTA DOCKER

- Introdução ao Docker

 Introdução ao Docker do ponto de vista como tecnologia esuas funcionalidades. Componentes necessários para oisolamento de recursos. Diferença entre imagens e containers.Arquitetura do Docker Engine e seus componentes. Diferençaentre máquina virtual e containers. Apresentação e explicaçãodo Docker Hub. Apresentação explicação dos produtosdisponibilizados pela Docker. Ferramentas para auxiliar noaprendizado.

- Introdução ao Docker

Apresentação e explicação dos requisitos para criação de umambiente de estudos e/ou desenvolvimento. Instalação econfiguração do Docker Desktop e Docker Engine no Ubuntu.Introdução a CLI do Docker.

- Ambiente de estudos e desenvolvimento

Introdução ao funcionamento de um container por debaixo dospanos. Criação de containers e apresentação dos parâmetrosdisponíveis. Explicação da diferença entre o Docker pull eDocker push. Apresentação e explicação dos comandosnecessários para administrar containers em execução.Demonstração sobre como executar comandos em umcontainers. Apresentação dos comandos para verificação doconsumo de recursos e processos e um container.Demonstração de como trabalhar com variáveis de ambienteem um container.

- Gerenciando containers Docker

Introdução aos tipos de rede. Entendimento sobre ofuncionamento do DNS em containers. Apresentação eexplicação dos comandos necessários para implantar egerenciar redes customizadas. Demonstração dos tipos derede funcionando.

- Gerenciamento de volumes Docker

Introdução ao funcionamento de volumes em containersDocker. Apresentação dos tipos de volumes. Entendimentosobre qual volume utilizar de acordo com a situação.Demonstração
dos tipos de volumes em funcionamento com containersDocker

- Gerenciando imagens Docker

Introdução ao funcionamento de imagens em containersDocker. Introdução ao arquivo Dockerfile. Apresentação eexplicação do funcionamento de camadas e cache em imagensDocker. Demonstração da criação de imagens e apresentaçãodos principais parâmetros do Dockerfile.

- Docker compose e Compose File

Introdução ao Docker Compose o binário. Introdução aoCompose File (o arquivo). Apresentação e demonstração dostipos de instalação do Docker compose. Demonstração decomo executar múltiplos contêineres com Docker compose.Demonstração de como fazer o build de uma imagem Dockerdurante a execução do Docker Compose. Demonstração decomo trabalhar com redes e volumes no Docker Compose.Apresentação e demonstração do uso de YAML Anchors,múltiplos arquivos de compose. Apresentação e demonstraçãode como trabalhar com arquivo de compose dinâmica usandovariáveis de ambiente.

- Orquestração de containers com Docker Swarm

Introdução a orquestração de containers. Apresentação eexplicação sobre os conceitos de cluster. Introdução aarquitetura de microservices. Demonstração de instalação econfiguração do Docker Swarm. Demonstração de comogerenciar nodes do cluster Swarm. Apresentação e explicaçãosobre redes no modo Swarm. Demonstração de deploy deserviços. Demonstração de como fazer o controle deagendamento dos serviços nos nodes. Demonstração de comousar o Docker Compose no modo Swarm. Demonstração decomo criar e gerenciar uma stack de serviços no swarm.Demonstração de como gerenciar serviços e stack de serviçosno Docker Swarm.

- Docker em produção

Introdução as melhores práticas de arquitetura para ambientede produção. Apresentação e explicação de possíveisproblemas no gerenciamento de serviços com Docker Swarm.Apresentação e explicação de componentes adicionais paradeploy de aplicações em arquitetura distribuida. Apresentaçãoe explicação do fluxo de trabalho manual de deploy.Apresentação e explicação do fluxo de trabalho com pipelineCI/CD.

# EMENTA GITLAB CI/CD

- Introdução ao GitLab CI/CD

Introdução aos conceitos de Continuous Integration (CI),Continuous Delivery (CD), Continuous Deployment (CD).Introdução ao modelo push-model. Apresentação e explicaçãode como funciona um pipeline CI/CD.

- Conceitos do GitLab

Introdução aos principais conceitos do GitLab. Apresentaçãodas opções disponíveis para configuração de um pipeline CI/CDflexível e eficiente.

- Pipeline CI/CD com GitLab

Apresentação do Fluxo de CI/CD usando Gitlab. Demonstraçãoprática do ciclo de preparação e configuração do pipelineCI/CD. Demonstração de como enviar uma imagem para oDocker Hub. Demonstração de como fazer o deploy deaplicações com Docker Compose.

- GitLab Runner

Introdução ao GitLab Runner. Apresentação e explicação daexecução SaaS e local. Apresentação e explicação dasfuncionalidades e benefícios de usar o GitLab Runnergerenciado. Demonstração de como controlar a execução dosJobs por localidade.

- Pipeline avançado

Apresentação e explicação de estratégias para tornar opipeline CI/CD totalmente dinâmico. Demonstração de comoconfigurar quando o Job deve ser executado. Demonstração decomo trabalhar com variáveis. Demonstração de comoconfigurar a dependência de jobs. Demonstração de comoconfigurar a esteira completa desde o ambiente dedesenvolvimento a produção.

# EMENTA KUBERNETES

- Introdução ao Kubernetes

Introdução ao conceito de Cloud Native. Introdução aoKubernetes e suas funcionalidades. Apresentação e explicaçãodo funcionamento de orquestração de containers comKubernetes.

- Conceitos do Kubernetes

Apresentação e explicação dos conceitos core do Kubernetes.Apresentação e explicação da arquitetura. Apresentação eexplicação dos objetos Kubernetes e seus casos de uso.

- Instalação e configuração do Kubernetes

Apresentação das maneiras de instalação e gerenciamento deum cluster Kubernetes. Apresentação das ferramentas deexecução do Kubernetes em ambiente de estudos edesenvolvimento. Apresentação do Rancher como ferramentade gerenciamento de cluster on-premise e Cloud.

- Deploy de aplicações no Kubernetes

Apresentação e explicação dos objetos mínimos para deployde uma aplicação no Kubernetes. Explicação do funcionamentode cada objeto. Demonstração dos Pod, ReplicaSet,Deployment. Explicação do funcionamento de Labels, Selectose Namespaces.

- Services e Ingress

Apresentação dos objetos necessários para comunicação entreas aplicações e acesso externo aos serviços. Demonstração daconfiguração de Services. Demonstração da Configuração doIngress

- Persistindo dados no Kubernetes

Introdução ao funcionamento dos dados em objetosKubernetes. Apresentação das funcionalidades parapersistência de dados. Demonstração da configuração para usodos diversos tipos de volumes.

# EMENTA GITOPS COM ARGO CD

- Introdução ao GitOps

Introdução ao conceito e benefícios do GitOps para Deploy deaplicações.

- Introdução ao ArgoCD

Introdução ao ArgoCD. Apresentação e explicação dosbenefícios e funcionalidades do ArgoCD.

- Conceitos do ArgoCD

Introdução aos conceitos do ArgoCD. Apresentação eexplicação dos casos de uso.

- Instalação do ArgoCD

Apresentação e explicação da arquitetura. Apresentação eexplicação das maneiras de instalação. Demonstração dainstalação do ArgoCD no Cluster Kubernetes.

- Preparando a aplicação para o Deploy

Introdução ao fluxo de trabalho com GitOps. Apresentação eexplicação da estrutura de repositórios para trabalhar comGitOps. Demonstração e configuração da etapa de mudança deimagem no repositório do GitOps.

- Deploy de aplicações no Kubernetes

Demonstração da configuração de uma App no ArgoCD.Demonstração da configuração de Deploy usando Helm.Demonstração da configuração de deploy multi-ambiente.Demonstração da configuração de deploy multi-cluster.


## COMO VAI FUNCIONAR


Aulas aos sábados das 14:00 as 18:00
Total de 16 sábados (4 meses) de aula e acompanhamento
Horário

Turma de sábado

| DATA | -                          | INSTRUÇÂO |
| --- | --- | --- |
|08/07/2023| - | Boas vindas  Introdução ao Treinamento  Curso Controle de versão com Git|
|15/07/2023| - | Aula de Git Introdução ao Gitignore e checkout, gitrestore  |
|22/07/2023| - | Curso de Docker |
|29/07/2023| - | Curso de Docker |
|05/08/2023| - | Curso Kubernetes |
|19/08/2023| - | Curso Kubernetes |
|26/08/2023| - | Curso Kubernetes |
|02/09/2023| - | Curso Kubernetes |
|09/09/2023| - | Curso Kubernetes |
|16/09/2023| - | Curso Kubernetes |
|23/09/2023| - | Curso Helm |
|30/09/2023| - | Curso Helm |
|07/10/2023| - | GitOps com ArgoCD |
|14/10/2023| - | Plantão geral de dúvidas |
|21/10/2023| - | Desafio Final + Encerramento |