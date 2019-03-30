# Pipeline

É a sequencia de atividades automatizadas para levar o código da máquina do desenvolvedor para o ambiente de produção.

## Essa expressão é uma abstração que envolve os processos

* Integração Continua (Continuous Integration)
* Entrega Continua (Continuous Delivery)
* Implantação Continua (Continuous Deployment)

## Objetivo

* Entregar código em produção de forma rápida, segura e consistente
* Tornar visível cada parte do processo de entrega do software
* Automatizar tudo o que for possivel.

## Integração Continua

O que é ?
R- É a capacidade de integrar features de softwares sem muito esforço.

Prática do XP, que encoraja desenvolvedores a integrar seu trabalho de forma mais frequente, para que problemas sejam detectados e corrigidos rapidamente.
O processo é: Dev recebe seus cards - contendo o Job a ser executado, desenvolve, testa, faz commit.
Padronizar commit, somente fazer commit na branch Master,
caso o código esteja 100% funcional. Não pode haver bugs
no status de Produção.

## Ferramentas para CI

Jenkins, TC, GO, Bamboo, CircleCI, AWS CodePipeline,
CloudBees, TravisCI.

## Requisitos para uma Integração Continua

* SCM - Sistema de Controle de Versão
* Processo automatizado de Compilação/Transpilação/Envio de arquivos HTML para o diretório do Servidor Web utilizado.
* Aceitação da Equipe.

## Entrega Continua

O que é ?
R- A entrega continua é uma extensão, ou melhor, um complemento ao processo de Integração Continua. Ela envolve o elemento Integração Continua, exatamente no que diz respeito a Automatização de Integrações, ou seja: Automatizar e ganhar tempo para a Equipe.

## Implantação Continua

O que é ?
Todas as etapas anteriores, com a aceitação Automatizada, isso quer dizer que: Quando o Dev acaba de Commitar o código, o código vai ser revisado, testado, integrado, tudo isso de forma automatizada, e ainda é trabalho do servidor de Integração Continua (no primeiro estágio do processo já é necessário Feedback, coloquei só aqui por motivos de melhor entendimento, mas saiba que é um dos pilares mais importantes, não deixe de dar feedbacks) - Dar feedbacks para TODOS os envolvidos no projeto.

### Como criar um Pipeline de implantação

Existem estratégias de auxilio ao processo.

1. Modelar o fluxo de valor e criar um esqueleto do processo.

2. Automatizar os processos de Compilação.

3. Automatizar os Testes.

4. Automatizar os processos de implantação.

5. Implementar estratégia de Entrega de Versão.

### Beneficios do Pipeline de implantação

* Processo confiável, previsivel e passível de repetição.
* Autonomia para as equipes entregarem seu trabalho.
* Redução de erros.
* Redução de estresse para lançar nova versão.

## Testes

Se não automatizarmos TESTES, muito provavelmente lançaremos Software SEM NENHUM Valor, de baixa qualidade, pois é sucetivel a erros por falhas humanas, e todas as outras empresas já usam esse modelo, se não for pra ser referencia, eu nem faço. Não teremos o ganho necessário caso continue fazendo testes de forma manual.

O Teste ideal, mais preferivel, é: Aquele teste mais barato de ser executado, de forma automatizada, ou seja, devemos encontrar os Bugs das aplicações sempre no teste mais rápido e barato, que geralmente são os Unitários, seguido por Testes de componentes automatizados, Testes de Integração Automatizados, Testes de API Automatizados, Testes de GUI Automatizados, e por fim, CASO NECESSÁRIO são executados testes Manuais.

**Telimetria, ou Monitoramento:** É necessário, uma das bases da Entrega de Valor, deve trabalhar em conjunto com Feedbacks, especialmente para Devs, e coletar taxas de melhorias, É AQUI QUE O SEU SALÁRIO DEVE FICAR MAIS GORDINHO. :) Após mostrar melhorias, se o seu salário não engordar, vá embora imediatamente, você não está sendo valorizado.
É importante a padronização de Stacks de ferramentas para a equipe, a abertura de cartões de Jobs (sim, a equipe deve ter acesso ao que cada Profissional está Responsável por entregar naquele determinado processo)

### Também é necessário integrar QUALIDADE e SEGURANÇA

***Qualidade e Segurança não andam separado do desenvolvimento e sustentação.***

Todos os envolvidos são responsáveis pela Qualidade e Segurança de cada projeto. Devemos pensar nesses itens em TODO O CICLO DE VIDA DO SOFTWARE.

<!-- Manifesto Ágil -->
<!-- O manifesto ágil, diz que a nossa maior -->
<!-- prioridade é SATISFAZER O CLIENTE, através -->
<!-- da entrega adiantada e contínua de -->
<!-- Software de Valor -->
<!-- e ainda salienta: -->
<!-- ENTREGAR SOFTWARE FUNCIONANDO COM FREQUENCIA -->
<!-- na escala de semanas até meses, com -->
<!-- preferencia aos períodos mais curtos. -->