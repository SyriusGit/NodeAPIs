npm i:
EXPRESS: webserver que vamos utilizar para a webapi;
CORS: pacote de segurança necessário para permitir comunicação futura com o front-end;
DOTENV: pacote de configuração para cuidar das variáveis de ambiente;
HELMET: pacote de segurança para dar uma blindada na nossa webapi;
MORGAN: pacote para login de requisição no terminal;
EXPRESS-ASYNC-ERRORS: pacote para conseguir capturar erros assíncronos.


-server.ts: módulo de inicialização do servidor web onde nossa webapi estará hospedada, módulo de infraestrutura;
-app.ts: módulo de configuração da webapi, módulo de aplicação;
-routers: pasta onde guardaremos os módulos de roteamento, que mapeiam os endpoints para as funções de controle;
-controller: pasta onde guardaremos os módulos de controle, que recebem as requisições roteadas e fazem os processos necessários;
-models: pasta onde guardaremos os módulos de entidades, que contém a especificação delas;
-repositories: pasta onde guardaremos os módulos de repositório, que contém as funções de leitura, exclusão, inserção, etc das entidades.