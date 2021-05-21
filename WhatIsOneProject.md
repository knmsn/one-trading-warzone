
# O que é o projeto da ONE?

O projeto da ONE é inicialmente focado no desenvolvimento de um sistema para gerenciamento, tratamento e cruzamento de dados vindos de sistemas parceiros usados na gestão interna da empresa One Investimentos.  
Simples, não? **Não!** :P  
Uma das funcionalidades especificas da plataforma seria a migração de dados da plataforma BTG para a plataforma interna da ONE. Sendo um total aproximado de 27 planilhas, com a soma total de 900 mil linhas sendo feito upload e comparação diária.  
De acordo com a necessidade do projeto, as stack a ser ultilizada foi levantada de acordo com as tecnologias que melhor se encaixariam no escopo. Dessa maneira, usamos as tecnologias:  
  
* ReactJS - FrontEnd
* NodeJs -> NestJs, PrismaJs e Graphql para o monolito central
* Python -> Panda/PyMysql para o micro-serviço de upload de planilhas
* MySQL - RDS AMAZON -> Banco de dados
* Instância EC2 - Medium - Acoplamento e deploy do backend + frontend
* Instância EC2 - Medium - Acoplamento e deploy do micro-serviço de upload e validação das planilhas
* AMAZON - SES - Serviço SMTP para envio de e-mails dentro da plataforma

[:arrow_backward:]  [Voltar para o inicio?](https://github.com/KoenomatachiSan/one-trading-warzone)

