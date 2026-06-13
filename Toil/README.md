# Redução de Toil – Gestão de Acessos

Projeto desenvolvido durante o MBA em Cloud Computing & DevOps com o objetivo de identificar atividades operacionais repetitivas, analisar seus impactos e propor estratégias de automação para redução de Toil.

## O que é Toil?

De acordo com os princípios de Site Reliability Engineering (SRE), **Toil** representa atividades manuais, repetitivas, reativas e que agregam pouco valor estratégico ao negócio, consumindo tempo operacional que poderia ser direcionado para melhorias contínuas e inovação.

A redução de Toil é uma das práticas fundamentais para aumentar a eficiência operacional, reduzir erros humanos e melhorar a experiência tanto das equipes técnicas quanto dos usuários finais.

---

## Cenário Analisado

O caso estudado foi o processo de **Gestão de Acessos**, frequentemente presente em ambientes corporativos.

### Atividades identificadas

#### Todo dia

Realizar manualmente a criação de contas e a liberação de permissões para novos colaboradores que ingressam na organização.

#### Toda semana

Revisar solicitações de acesso pendentes e ajustar permissões de colaboradores que mudaram de função ou unidade.

#### De vez em quando

Executar auditorias para identificar acessos indevidos ou contas pertencentes a pessoas desligadas da empresa.

#### Nunca (mas deveria)

Automatizar o processo de onboarding e concessão de acessos para reduzir dependência de atividades manuais e aumentar a confiabilidade do processo.

---

## Problemas Identificados

* Dependência excessiva de intervenção humana;
* Alto consumo de tempo operacional;
* Suscetibilidade a erros manuais;
* Risco de permissões incorretas ou excessivas;
* Dificuldade de rastreabilidade;
* Processos reativos ao invés de preventivos;
* Aumento da carga operacional das equipes de suporte.

---

## Proposta de Melhoria

Foi proposta a automação do processo de gestão de acessos, utilizando abordagens como:

* Provisionamento automatizado de contas;
* Fluxos de aprovação padronizados;
* Integração entre sistemas de RH e ferramentas de identidade;
* Self-service controlado para solicitações recorrentes;
* Aplicação automática de perfis de acesso conforme função;
* Auditorias periódicas automatizadas.

---

## Benefícios Esperados

* Redução significativa do esforço operacional repetitivo;
* Menor incidência de erros humanos;
* Maior velocidade no onboarding de colaboradores;
* Melhoria da experiência dos usuários;
* Maior rastreabilidade das ações realizadas;
* Fortalecimento da governança e da segurança da informação;
* Liberação do tempo das equipes técnicas para atividades de maior valor agregado.

---

## Principais Aprendizados

Este estudo reforçou a importância de identificar atividades que geram baixo valor estratégico e consumem recursos operacionais de forma recorrente.

Mais do que automatizar tarefas, reduzir Toil significa repensar processos para torná-los mais eficientes, seguros e sustentáveis ao longo do tempo.

Durante esta atividade, aprofundei conceitos relacionados a:

* Site Reliability Engineering (SRE);
* Gestão de Identidades e Acessos;
* Automação de processos;
* Governança operacional;
* Eficiência e melhoria contínua;
* Análise crítica de processos manuais.

---

## Observações

Este material possui finalidade educacional e representa a aplicação prática dos conceitos estudados durante o MBA em Cloud Computing & DevOps.

O objetivo deste repositório é documentar minha evolução técnica e demonstrar a capacidade de identificar oportunidades de melhoria operacional por meio da automação e da redução de atividades repetitivas.
