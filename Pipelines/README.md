# CI/CD Pipelines

Este diretório reúne estudos e modelagens de pipelines desenvolvidas durante o MBA em Cloud Computing & DevOps da Impacta.

Mais do que representar um fluxo estático, estes materiais documentam a evolução do meu entendimento sobre Integração Contínua, Entrega Contínua, Observabilidade, Infraestrutura como Código e governança em processos de entrega.

---

## Objetivos

* Compreender o ciclo completo de entrega de aplicações modernas;
* Identificar ferramentas utilizadas em cada etapa do processo;
* Estudar diferentes abordagens para automação e deploy;
* Consolidar conceitos relacionados a qualidade, segurança e observabilidade;
* Desenvolver uma visão crítica sobre arquitetura de pipelines.

---

# Pipeline 1 – Visão Generalista do Ecossistema DevOps

![Pipeline 1](pipeline-1.jpg)

A primeira proposta teve como objetivo mapear, de forma ampla, os principais componentes presentes em pipelines modernas.

Ao invés de representar uma implementação específica, esta pipeline foi utilizada para explorar diferentes ferramentas e possibilidades adotadas pelo mercado.

## Conceitos abordados

### Versionamento

* GitHub
* Git

### Build e Automação

* GitHub Actions
* Jenkins
* GitLab CI

### Qualidade e Testes

* SonarQube
* Selenium

### Armazenamento de Artefatos

* AWS CodeArtifact
* Azure DevOps Artifacts
* Docker Hub
* Nexus Repository

### Deploy

* AWS CodeDeploy

### Governança

* Gates de aprovação

### Observabilidade

* Conceitos de monitoramento e rastreabilidade durante o processo de entrega.

---

# Pipeline 2 – Refinamento e Consolidação da Arquitetura

![Pipeline 2](pipeline-2.jpg)

Após compreender o ecossistema como um todo, foi desenvolvida uma segunda proposta com foco em um fluxo mais coeso e alinhado às necessidades de uma entrega moderna.

Nesta etapa, as ferramentas deixaram de ser apenas alternativas possíveis e passaram a compor uma arquitetura integrada.

## Fluxo estudado

DEV → Jira → GitHub → GitHub Actions → SonarQube → Docker → Amazon ECR → Trivy → AWS CodeDeploy → Kubernetes

### Gestão de Segredos

* AWS Secrets Manager

### Observabilidade

* Dynatrace (OneAgent + OpenTelemetry)

### Gestão de Incidentes

* ServiceNow

### Feedback e Melhoria Contínua

* Integração do retorno operacional ao backlog através do Jira.

---

## Evolução do desenho e reflexões

Durante a elaboração da segunda pipeline, foi possível perceber oportunidades de melhoria arquitetural.

Um dos principais pontos observados foi a posição do Terraform dentro do fluxo principal.

Inicialmente, a Infraestrutura como Código foi representada como parte do pipeline de aplicação. Entretanto, após revisitar o desenho e refletir sobre responsabilidades e governança, entendo que o provisionamento de infraestrutura poderia ser tratado em uma pipeline independente.

Essa separação permitiria:

* Maior desacoplamento entre infraestrutura e aplicação;
* Reutilização dos componentes de infraestrutura;
* Redução de riscos operacionais;
* Maior controle sobre mudanças em ambientes críticos;
* Melhor aderência às práticas de governança.

Mais do que identificar uma possível melhoria, essa reflexão representa a evolução do meu entendimento sobre práticas DevOps e demonstra a importância da revisão contínua das soluções propostas.

---

## Principais Aprendizados

Ao longo destas atividades, aprofundei conhecimentos relacionados a:

* Integração Contínua (CI);
* Entrega Contínua (CD);
* Infraestrutura como Código (IaC);
* Gestão de segredos;
* Testes automatizados;
* Segurança em pipelines;
* Gestão de artefatos;
* Estratégias de deploy;
* Observabilidade;
* Redução de Toil por meio da automação;
* Importância da análise crítica e refinamento contínuo das arquiteturas propostas.

---

## Observações

Este material possui finalidade educacional e tem como objetivo registrar minha evolução técnica na área de Cloud e DevOps.

As pipelines apresentadas representam o processo de aprendizado e aplicação prática dos conceitos estudados durante o MBA, evidenciando não apenas a execução das atividades, mas também a capacidade de análise, revisão e melhoria contínua das soluções desenvolvidas.
