# Day 2

### Foundation

- Necessário para que seja possível rodar as informações direitinho na AWS

- ![](/Users/mariaadelia/Desktop/Programação/AWS%20Expert/Notebook/Images/Foundation.png)
  
  - **Root Account**
    
    - A conta principal de todos os recursos da AWS
    
    - A partir dessa conta é possível criar subcontas, organizações, etc. A partir dessa conta é feita a divisão das coisas
    
    - Serve para iniciar novas contas na AWS e realizar compras, receberemos cobranças, etc. na AWS
    
    - Você não usa essa conta para subir recursos, mas sim para gerenciar outras (não é boas práticas rodar serviço na root)
    
    - Root account não deve permitir que nada seja deployado na root account porque a função dela é ser uma conta para gerenciar outras
    
    - Root account é uma account normal, ela só vira root a partir do momento que você começa a criar outras contas abaixo dela
  
  - **Organisational Unit (UO)**
    
    - Eu posso fazer pequenas contas na qual cada uma terá uma regra organizacional que eu posso definir
    
    - Uma forma de categorizar/agrupar as contas (ex: dev, prod, QA)
    
    - O que vai guiar essa criação ou não, é o fator de ter ou não subcontas
  
  - **Accounts (Contas)**
    
    - Essas são as sub accounts que irão rodar serviços (diferente da root account)
    
    - Ela é criada da mesma forma que a root account (há outras formas de criar essas contas também) e acaba estando relaciona a essa root
    
    - Características: nome da conta e email único (não pode ter mais de uma conta com o mesmo email)
      
      - Dentro das empresas, nesse momento do email único, o que as empresas acabam fazendo é: criam emails fakes para essas sub accounts ou coloca o email de uma pessoa da empresa
      
      - Dicas: não use o email de uma pessoa para criar conta, use o email do time (é importante criar um email de time) pois tem emails que precisam ser lidos. Quando você não tem essa interação, você pode ter um score baixo para com a amazon
    
    - f
  
  - d

- (parei na AWS Accounts, part2)

##### Xxx

- *Xxx*
  - Xxx
