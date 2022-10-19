# AWS Expert - Day 1

### What is Cloud Computing?

- poder rodar os meus serviços em algum lugar que eu consiga fornecer isso como uma plataforma para alguém, que eu consiga escalar esses serviços, trazer uma elasticidade

##### Principais características e vantagens do *Cloud Computing*

- *Agilidadade (Agility)*
  - Trazer agilidade para o time de infra (esses times deixaram de lidar com o hardware físico para algo "online", sem mais datacenters próprios)
- *Manutenção (Maintenance)*
  - O time de infra não é mais responsável por ter que cuidar dessa manutenção (o que acabou tendo uma redução de custos pois *datacenters* são caros e precisam de uma grande quantidade de pessoas para cuidar disso)
- *Confiabilidade (Reliability)*
  - Pois com essa "terceirização", os especialistas focados nisso irão tomar conta
- *Segurança (Security)*
  - Apesar de ainda ser necessário se preocupar com a segurança, o cloud tem uma série de ferramentas relacionadas a segurança (e a preocupação com a segurança do *datacenter* próprio, não é mais necessário pois a empresa de clouding que você contratou será responsável por isso)
- *Performance*
  - É possível ter uma maior performance pelo cloud (só que, para isso, você precisa pagar mais, lembrando que no cloud você paga por demanda), pois em um *datacenter* próprio, você teria que fazer toda uma movimentação para trazer uma melhor performance
- *Escalabilidade (Scalability)*
  - É simple fazer a escalabilidade em geral e sobre demanda (você paga mais quando você usa mais, você não fica pagando quando você não tem necessidade de usar mais)
- *Custo e Elasticidade (Cost and Elasticity)*
  - Como o custo está relacionado ao quanto você usa e como você pode aumentar e diminuir a quantidade de servidores que usará, o cloud traz essa vantagem de controle dos custos e da elasticidade de usar mais ou menos de acordo com a demanda
  - Essa *elasticidade* apesar de ser imensa ela **não** é **infinita**

Se você tiver uma arquitetura que **não se encaixe** com o *cloud*, ao invés de trazer todas essas vantagens, vai trazer na verdade **prejuízo e mais dificuldades**

**Soft limit** é um limite que você **faz uma requisição na AWS para que eles aumentem esse limite** (ou seja, **o que você está demandando ainda está dentro das capacidades físicas do *datacenter* da AWS**)

**Hard limit** é o limite que você **não pode aumentar**, pois é o **limite da capacidade do datacenter da AWS**

##### Principais características e vantagens do *Cloud Computing* (**segundo o NIST (The National Institute of Standards and Technology)**)

- *Autoatendimento sob demanda (On demand self service)*
- *Amplo acesso a rede (Broad network access)*
- *Agrupamento de recursos (Resource pooling)*
- *Elasticidade rápida (Rapid elasticity)*
- *Serviço que pode ser medido (Measured service)*

### Modelos de Cloud (Service models)

- **IaaS (Infrastructure as a Service)**
  
  - Infraestrutura como serviço
  - Tenho minha infraestrutura sendo disponibilizada por alguém no mercado como serviço

- **PaaS (Plataform as a Service)**
  
  - Plataforma como serviço
  - Você não precisa se preocupar com o que está por trás, você coloca seu código nessa cloud e essa plataforma irá devolver seu sistema rodando (ex: Heroku)

- **FaaS (Function as a Service)**
  
  - Função como serviço
  
  - Utilizar um microsserviço pela *cloud* (ex: um envio de email, etc).

### Deployment models

- **Private Cloud***
  - É seu, é privado (a plataforma é privada)
- **Public Cloud***
  - Qualquer um pode usar a plataforma (AWS, Google Cloud, etc), mas não necessariamente os seus recursos (as suas api's por exemplo)
- **Hybrid Cloud***
  - Você pode ter tanto a *private* quanto a *public* como *cloud*, você utiliza dois modelos de *cloud*
- **Multicloud**
  - Poder rodar todos os seus serviços em todas as *clouds* (não é muito utilizado) evitando a dependência a uma *cloud* específica
- **Community**
  - Empresas se reunem e constroem um *cloud* que todas as empresas, que se uniram, utilizarão


