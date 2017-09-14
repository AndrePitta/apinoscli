# apinoscli
Desenvolvendo a Aplicação APINOSCLI.
É um RESTful API em Node.Js & Express.Js com MongoDb

Desenvolvendo uma aplicação, apinoscli, RESTful API - Nde.Js & Express.Js e MongoDb


Definir a estrutura do projeto a ser desenvolvido (esqueleto)

Definir os pacotes de dependência do Node no projeto através do
arquivo package.json

Configurar o Express.Js para poder levantar o serviço do projeto desenvolvido.

Criar o modelo da Base de Dados pelo MongoDb.

Definir o modelo do projeto através do Mongoose.

Criar a classe modelo do projeto.

Criação das rotas através do Express.Js

Criar o método POST (Criar Usuário)

Criar o método GET (Selecionar todos os Usuários)

Criar o método GET:/id (Selecionar um Usuário específico)

Criar os demais métodos para a rota Usuário

Criar os demais métodos para as outras Rotas

OBS: install node.Js LTE, install MongoDb criando o arquivo

a) criados os diretótios: mkdir c:\data\db e mkdir c:\data\log

b) criado o arquivo mongod.cfg que specifica ambos systemLog.path and storage.dbPath, conforme abaixo

    systemLog:
        destination: file
        path: c:\data\log\mongod.log
    storage:
        dbPath: c:\data\db
        
c) instalar o mongod.cfg => "C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" --config "C:\Program Files\MongoDB\Server\3.4\mongod.cfg" --install

d) instalar o MongoDb como sserviço automático => sc.exe create MongoDB binPath= "\"C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe\" --service --config=\"C:\Program Files\MongoDB\Server\3.4\mongod.cfg\"" DisplayName= "MongoDB" start= "auto"
