# Gatewy Cat 😸
## Integração de Serviços e Pagamentos.

[![R|RESENDE](https://i.ibb.co/XyT92vs/logo-r.png)](https://resende.dev.br/)

GatewayCat é um aplicação de serviços e pagamentos em nuvem, pronto para ser integrado em sistemas web ou desktop,
API de Pagamento Baseado em Soluções de serviços financeiro e entre outros.


- Integração com Varios Gateway de Pagamento Brasileiro
- Dashboard de Gerenciamento e Scripts com integrações terecerizada e-commerces & sistemas web 
- ✨Saas✨

## Características
- API DE PAGAMENTO
- API SERVIÇOS
- DASHBOARD BÁSICO

## Tecnologias

GatewayCat usa vários projetos de código aberto para funcionar corretamente:

- [Node.JS] - Eventos de E/S para o back-end
- [Express] - Estrutura de aplicativo de rede rápida Express Node.JS 
- [jQuery] - jQuery é uma biblioteca livre que contém funções da linguagem de programação JavaScript
- [HandlebarsJS] - Modelos semânticos
- [Socket.IO] - Comunicação bidirecional e de baixa latência para todas as plataformas
- [Sequelize] - Modelagem de dados
- [SQLite] - Banco de Dados

E é claro que o próprio GatewayCat é de código aberto com um [repositório público] [gatewaycat] no GitHub.

## Instalação

GatewayCat requer [Node.js](https://nodejs.org/) v16+ para ser executado.

Instale as dependências e devDependencies e inicie o servidor.

```sh
cd gatewaycat
npm i
npm start
```

Para ambientes de produção...

```sh
npm run dev
```

## Configuração .ENV
O arquivo .env geralmente é mantido fora do controle de versão, pois pode conter chaves de API e senhas confidenciais. Um arquivo .env.example separado é criado com todas as variáveis ​​de ambiente necessárias definidas, exceto as sensíveis, que são fornecidas pelo usuário para seus próprios ambientes de desenvolvimento ou comunicadas em outro lugar aos colaboradores do projeto. Os colaboradores do projeto então copiam independentemente o arquivo .env.example para um .env local e garantem que todas as configurações estejam corretas para seu ambiente local, preenchendo as chaves secretas ou fornecendo seus próprios valores quando necessário. Neste uso, o arquivo .env deve ser adicionado ao arquivo .gitignore do projeto para que nunca seja confirmado por colaboradores. Esse uso garante que nenhuma senha confidencial ou chave de API estará no histórico de controle de versão, portanto, há menos risco de violação de segurança e os valores de produção nunca terão que ser compartilhados com todos os colaboradores do projeto.

Adicione a configuração do seu aplicativo a um arquivo .env na raiz do seu projeto. Certifique-se de que o arquivo .env seja adicionado ao seu .gitignore para que não seja feito check-in no código

```sh
# Application  
NAME_APP=Gateway Cat
PORT_APP=8000
HOST_APP=gatewaycat.com.br
SECRET_APP=1234567BrasilSecret
VERSION_APP=1.0.0
DATABASE_APP=./private/app.sqlite3

# Websocket
HOST_WS=ws.gatewaycat.com.br
```
Verifique a implantação navegando até o endereço do servidor em seu navegador preferido.

```sh
127.0.0.1:8000
```

## License
MIT

**Software Livre, claro que sim!**

[//]: # (Esses são links de referência usados ​​no corpo desta nota e são removidos quando o processador de remarcação faz seu trabalho. Não há necessidade de formatar bem porque não deve ser visto. Obrigado, então - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [gatewaycat]: <https://github.com/victorresende069/gatewaycat>
   [git-repo-url]: <https://github.com/victorresende069/gatewaycat.git>
   [Victor Resende]: <https://resende.dev.br/et>
   [Node.JS]: <http://nodejs.org>
   [jQuery]: <http://jquery.com>
   [express]: <http://expressjs.com>
   [HandlebarsJS]: <https://handlebarsjs.com>
   [Socket.IO]: <https://socket.io>
   [Sequelize]: <https://sequelize.org>
   [SQLite]: <https://www.sqlite.org>
   
