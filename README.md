# DevOps-SRE
Arquivos para aprendizado/fixação de conteudos relacionados à Cultura DevOps, e SRE - Site Reliability Engineering - Jeito Google de manutenir sites.

# DevOps

**O que é DevOps:**
-É a combinação de culturas e filosofias, práticas e ferramentas que aumentam a capacidade de uma empresa distribuir aplicativos e serviços.
-Consiste no alinhamento de todo o time envolvido no projeto, englobando processos, ferramentas e responsabilidades.
-Representa uma mudança na cultura de TI com foco na entrega rápida através da adoção de práticas ágeis.
-Visa melhorar empatia no time.

**História DevOps:**
- Surgiu da comunidade
- 2001 no manifesto agil
- Mudança na entrega do software
- União entre cliente e negocio
- Entregas menores e constantes
- 2003 google estruturou o SRE (Site Reliability Engineering)
- GIT surgiu em 2005 (O Puppet tb, ele serve pra automatizar configurações.)
- Patrick Debois (Pronuncia: Patric Debuá) pai do termo DevOps, após ver palestra do Flickr 10+ deploys por dia: Dev & Ops https://www.youtube.com/watch?v=LdOe18KhtT4
- Ansible lançado em 2012 para automatizar processos
- 2013 O Projeto Fenix (The Phoenix Project) |Livro

**Pilares do DevOps:**
- Cultura: colaborativa, união
- Automação: ferramentas de automação, pipelines automatizada
- Medição: métricas do ciclo, monitoração e logs
- Compartilhamento: feedback, responsabilidades
- Lean:Técnica desenvolvida pela Toyota, visando PERFEIÇÃO

**Caracteristicas do DevOps:**
- Desenvolvimento Ágil;
- Ciclo de entregas rápidas de versões do software;
- Diminuição na complexidade do software;
- Integração Contínua (CI);
- Entrega Contínua (CD);
- Gerencia de Configurações;
- Centralização de logs;
- Monitoração e coleta de métricas;
- Infra como código;
- Ambiente Automatizado;

**Beneficios do DevOps:**
- Melhor comunicação e colaboração entre a equipe
- Melhor qualidade e maior frequencia de entrega
- Redução de falhas na implementação de mudanças
- Aumento do valor do negócio

Metodologias base pro DevOps:
- Lean
- Scrum
- Kanban

***SEMPRE OLHE PARA O PROJETO E PROCURE ONDE ELE PODE SER MELHORADO***

# SRE - Jeito Google de manutenir sites.

Um dos criadores, foi: Ben Treynor
Ele é Engenheiro de Software, não SysAdmin. ;)

Times de tamanho razoavel com crescimento da infraestrutura, o tanto que for.

Time de Dev: Focado em Novas Features, e correções.
Time de Ops: Focado na disponibilide, e estabilidade.

Automação dos processos manuais.
Principios:
- Abraçar o risco.
- Estabelecer indicadores.
- Nivel de objetivo do serviço.

Eliminar TOIL
(Serviços repetitivos que simplismente acontecem e não são evitaveis.)

Monitoramento
Mantenha métricas simples.

Automatização

Engenharia de Release

Simplicidade

## DevOps ou SRE, eis a questão ? 
Eu acredito serem assuntos complementares, pois são focos parecidos com objetivos bem definidos
onde é possivel agregar valor com aplicação de parte de ambos modos de gestão de Infraestrutura.
Alguns autores, dizem que é uma boa prática cada repositório ter ao menos um arquivo de configuração de ambiente em seu repositório com uma breve descrição de uso, para uma fácil reprodução e teste.

A partir daqui, copiado de: https://gitlab.com/gutocarvalho/devops-tips/blob/master/estudos.md para servir como referencia de estudos.
Muitas pessoas perguntam o que devem estudar ou quais cursos devem fazer para entrar de cabeça no mundo DevOps.
Não é uma resposta fácil, mas tenho algumas indicações.

1. Vídeos

10 Deploys per day at Flickr
Esse palestra foi a ignição que faltava para a criação do movimento/cultura DevOps em 2009.
https://www.youtube.com/watch?v=LdOe18KhtT4

Entenda as origens DevOps
Vídeo rápido de Damon Edwards (devopsdays core member) acerca das origens do movimento, recomendo.
https://www.youtube.com/watch?v=o7-IuYS0iSE

What is DevOps? - In Simple English
Vídeo curtinho do rackspace que também ajuda.
https://www.youtube.com/watch?v=_I94-tJlovg

DevOpsConf - DevOps State of the Union (John Willis)
Palestra do John Willis (devopsdays core member) na DevOpsCon 2015 sobre o estado do DevOps após 5 anos de seu surgimento.
https://www.youtube.com/watch?v=8rM8lYaMVBE

Five Years of DevOps (Patrick Debois)
Patrick Debois o criador do DevOpsDays e do termo DevOps fala o que achou dos últimos 5 anos de DevOps.
https://www.youtube.com/watch?v=uRMV6tT_mu0

2. Acrônimos
Entenda o que é CAMS
http://devopsdictionary.com/wiki/CAMS
Entenda o que é CALMS
http://whatis.techtarget.com/definition/CALMS
Entenda o que é ICE
http://radar.oreilly.com/2015/01/devops-keeps-it-cool-with-ice.html
Entenda o que é DevSecOps
 http://www.devsecops.org/blog/2015/2/15/what-is-devsecops

3. ROTEIRO DE ESTUDOS
Essa sugestão de estudos é baseada no CAMS do Willis e Edwards.

3.1  Cultura

Estude a metodologia ágil de desenvolvimento (Ágile, XP)
Estude metodologias ágeis em geral
- Scrum
- Kanban
- Lean
Entenda o que é uma cultura de colaboração e feedback.

Faça um exercicio e tente enxergar os principais problemas culturais do
seu time/organização e encontre uma forma corrigir tais problemas adaptando esses métodos.

3.2 Automação

Estude virtualização (Virtualbox, Vagrant)
Estude cloud computing (Amazon, DigitalOcean, Azure)
Estude Mark Burgess e gerência de configurações (Chef, CFEngine)
Estude infraestrutura como código (Ansible, Terraform)
Conheça pelo menos duas ferramentas de Gerência de Configuração (CFEngine e Puppet)
Conheça pelo menos duas ferramentas de Orquestração (Fabric e Ansible)
Entenda o que é VCS (Version Control System)
Estude GIT pra valer
Estude workflows de desenvolvimento usando GIT (olhe os projetos opensource)
Estude Continuous Integration
Estude Continuous Delivery
Estude Continuous Deployment
Estude TDD/BDD/ATDD
Estude Load Testing
Estude Stress Testing
Estude Security Testing
Estude Containers e Docker (containerd e runc são boas alternativas ao docker, o funcionamento é parecido)
Estude Microservicos
Estude ferramentas para fazer provisionamento automatizado
Estude ferramentas de autoserviço
Estude sistemas Unix e Linux
Estude networking
Estude e domine pelo menos 2 linguagens interpretadas (Ruby e Python)
Conheça pelo menos 1 stack de cada linguagem
Estude a linguagem shell

Labs sugeridos

Tente subir uma stack full de automação (ex. puppet)

Tente automatizar confs simples do OS (ex. centos)
Tente automatizar a instalacao e configuracao de um APP (ex. apache ou nginx)


Tente provisionar VMs ou Containers de forma automatizada via autoserviço
Tente construir um pipeline de entrega

Indo desde o commit, passando por build, testes até o deploy em vm e container




3.3 Avaliação/Métricas

Entenda o que são métricas e pq são importantes
Estude real-time-metrics
Estude ferramentas APM
Conheca bem pelo menos duas ferramentas de monitoramento (Nagios/Zabbix)
Estude algum stack para tratamento de logs (ELK)
Estude algum stack para coleta e armazenamento métricas (Collectd/Statsd/Graphite/Graphana)

Labs sugeridos

Tente subir uma stack full de gestao de logs (ex. ELK)

Coloque diversos APPs para jogar dados lá


Tente subir um stack full de gestao de dados

Gere dados, colete, armazene e visualize com essa stack (ex. Graphite/Graphana)




3.4 Compartilhamento

Entenda a cultura de dividir responsabilidades
Entenda a cultura Blameless
Aprenda a compartilhar ferramentas entre todos os times
Aprenda a compartilhar código entre todos os times
Aprenda a compartilhar informações e dados
Procure sempre melhorar o processo de comunicação
Entenda como funcionam times de produtos
Ofereça feedback constante entre os times
Volte pra cultura  e reinicie o ciclo até aqui
Entenda e pratique Dojos
Entenda os Hackerspaces
Entenda os Hackatons


Cada eixo desse do roteiro de estudos tem cursos disponíveis no mercado, documentação farta online, artigos variados na rede.
Evite procurar formação DevOps, o ideal é que crie o seu roteiro de estudos.
Se encontrar formação DevOps por ai, tome muito cuidado para não ser uma empresa inventando algo só para faturar em cima da Buzzword.
Como voce viu DevOps é algo amplo, dificil de colocar em um curso de 24 ou 40 horas.
Agora é começar os estudos, divirta-se!
