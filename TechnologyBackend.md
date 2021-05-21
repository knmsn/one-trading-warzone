

# Tecnologias - Backend
Dentro do projeto usamos algumas tecnologias especificas para o desenvolvimento.

**WebService - NestJS**: Framework usado para criar os e e ndpoints dar suporte para o web-service graphql da aplicação.  
https://nestjs.com/

**GraphQL - Gerenciamento de requisições**: Usamos a ferramenta GraphQl para facilitar o tratamento de dados e a economia de processamento do servidor, deixando a opção do que será retornado para o frontend decidir.  
https://graphql.org/

**NestJs - Gerenciamento de requisições**: Usamos a ferramente de controllers do nestjs para administrarmos conexão com todo tipo de micro-serviço externo ao monolito. Por exemplo, o micro-serviço de upload de planilha só pode ser usado se ouver uma requisição no endpoint REST do controller do nestjs.  
https://nestjs.com/  

**Gerenciamento de banco de dados - PrismaJS** - Usado especialmente pela sua segurança e facilidade, essa ferramenta nos permite uma visão clara do banco de dados e dos seus relacionamentos, alem de outras ferramentas nativas como o introspect e a opção de modificação e "listen" de planilha do banco de dados em tempo real.
https://prisma.io/

** Monitoramento de banco de dados - DudeProject** - Essa library, desenvolvida por mim mesmo, tem dentre suas funcionalidades, a opção de verificar os usuários que estão conectados no banco e rastrea-los em tempo real.  
https://github.com/KoenomatachiSan/DudeSecurity-lib-python?fbclid=IwAR27nub2A3dQ6PF3DXTd7JY_FIFNgHzMBp3DMuqM57lR2ZB5MxSBNVpY_RA

**Gerenciamento de banco de dados - PyMysql** -  Devido a simplicidade da complexidade das querys de inserção no banco de dados a partir do micro-serviço não foi necessário a ultilização de um ORM complexo, por esse motivo usei o PyMysql para estabelecer conexão com o banco sempre que o micro-serviço for chamado e fazer as modificações no banco de dados. https://pypi.org/project/PyMySQL/

**Comparação e tratamento de dados - PANDA ** - Essa library nos dá diversas funcionalidades de manipulação de arquivos e big-data, por esse motivo é usada para a leitura e comparação dos dados do banco de dados e também das big-planilhas enviadas.

[:arrow_backward:]  [Voltar para o inicio?](https://github.com/KoenomatachiSan/one-trading-warzone)

