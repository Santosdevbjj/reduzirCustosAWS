## RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS.

**Data:** 21/06/2025
**Empresa:** Abstergo Industries
**Responsável:** Sergio Santos

**Introdução:**

Este relatório detalha a proposta de implementação de serviços AWS na Abstergo Industries, com o objetivo primordial de reduzir custos operacionais imediatos e otimizar a infraestrutura de TI.

 Como a empresa não possui infraestrutura de cloud atualmente, a adoção estratégica da AWS representa uma oportunidade única para construir uma base sólida e economicamente eficiente desde o início.


**Descrição do Projeto:**

O projeto de otimização de custos será dividido em três etapas focadas na implementação de serviços AWS que entregam valor financeiro tangível e rápido.

 Cada etapa visa substituir ou otimizar áreas que tipicamente representam grandes despesas em ambientes 
on-premise, ou que seriam excessivamente dispendiosas em uma migração sem planejamento.


## **Etapa 1:** 

**Otimização de Custos** de Computação com AWS Lambda.

**Nome da Ferramenta:** AWS Lambda

**Foco da Ferramenta:** O AWS Lambda é um serviço de computação serverless que permite executar código sem provisionar ou gerenciar servidores. Você paga apenas pelo tempo de computação consumido.

**Descrição de Caso de Uso:** Para uma farmácia, o Lambda pode ser utilizado para processar pedidos online, atualizar estoques em tempo real, gerar relatórios de vendas em horários programados, ou para operações pontuais de processamento de dados. 

Por exemplo, em vez de manter servidores 24/7 para processar pedidos que chegam esporadicamente, o Lambda executa a função de processamento apenas quando um novo pedido é recebido, eliminando o custo de servidores ociosos.

**Principal Ganho:** Redução drástica de custos de infraestrutura e operação. Não há custos fixos com servidores; a cobrança é baseada estritamente no uso, o que é ideal para cargas de trabalho intermitentes ou variáveis de uma farmácia.



## **Etapa 2:**

**Armazenamento e Distribuição de Conteúdo Otimizados** com Amazon S3 e Amazon CloudFront

**Nome da Ferramenta:** Amazon S3 (Simple Storage Service) e Amazon CloudFront

**Foco da Ferramenta:** Amazon S3 oferece armazenamento de objetos escalável, durável e de baixo custo. Amazon CloudFront é um serviço de rede de entrega de conteúdo (CDN) que acelera a distribuição de conteúdo estático e dinâmico, armazenando-o em cache em locais próximos aos usuários.

**Descrição de Caso de Uso:** O S3 será usado para hospedar todo o conteúdo estático do site da farmácia (imagens de produtos, CSS, JavaScript, PDFs de bulas) e backups de dados.

 O CloudFront distribuirá esse conteúdo globalmente, garantindo carregamento rápido para os clientes e reduzindo a carga nos servidores de aplicação. 

Isso evita a necessidade de servidores de arquivos dedicados e otimiza a banda larga.

**Principal Ganho:** Otimização de custos de armazenamento e largura de banda, além de melhora significativa na experiência do usuário devido à alta velocidade de carregamento do site.

 O modelo de pagamento "pague pelo que usar" do S3 é extremamente econômico para armazenamento, e o CloudFront reduz os custos de transferência de dados ao servir conteúdo de cache.


## **Etapa 3:**

**Gerenciamento de Bancos de Dados** com Custo-Benefício via Amazon RDS
**Nome da Ferramenta:** Amazon RDS (Relational Database Service)

**Foco da Ferramenta:** O Amazon RDS simplifica a configuração, operação e escalabilidade de bancos de dados relacionais na nuvem. 
Ele gerencia tarefas administrativas comuns como provisionamento, patching, backup e monitoramento.

**Descrição de Caso de Uso:** Para o banco de dados da farmácia (registros de clientes, produtos, transações de vendas), o RDS elimina a necessidade de comprar, instalar e manter hardware de servidor de banco de dados e licenças de software caras. 

Podemos optar por motores como PostgreSQL ou MySQL, que são de código aberto e, portanto, não têm custo de licença. 

O RDS permite dimensionar o banco de dados conforme a necessidade, evitando o superprovisionamento inicial.


**Principal Ganho:** Redução significativa dos custos de licenciamento de software e infraestrutura de banco de dados, além da eliminação da complexidade e dos custos de gerenciamento operacional de um banco de dados on-premise.

 A escalabilidade permite otimizar os custos ao pagar apenas pelos recursos de computação e armazenamento necessários.


**Conclusão:**

A implementação estratégica do AWS Lambda, Amazon S3/CloudFront e Amazon RDS na Abstergo Industries tem como expectativa uma redução substancial nos custos de infraestrutura de TI e operações, ao mesmo tempo em que aumentará a eficiência, a escalabilidade e a disponibilidade dos serviços digitais da farmácia.

Esses serviços, com seu modelo de pagamento por uso e gerenciamento simplificado, eliminam grandes despesas de capital (CAPEX) e transformam custos fixos em variáveis (OPEX), oferecendo uma flexibilidade financeira sem precedentes.


Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa, sempre com foco na otimização de custos e na inovação.


**Anexos:**

 * Estimativa de Custos AWS (com base em casos de uso genéricos da farmácia)

 * Diagrama de Arquitetura Simplificado

 * Guia de Primeiros Passos com cada serviço



**Assinatura do responsável pelo projeto:**
           Sergio Santos









