# -NETCore-3.1-NET5-6---C-API---Arquitetura-com-DDD

- Topicos do curso:

Introdução ao .NET Core, VsCode, Command Line do .NetCore, NuGet, Entity Framework, Api, Microsservice, Rotas, Restfull, DDD (Domain Driven Desing)

Versão: NETCore-3.1
- Criar Arquitetura do Projeto do Zero
- Implementar Entidades e Repositório com MySQL
- Implementar Service
- Implementar Aplicação e Endpoints
- Implementar o SQL-Server na API


- o que será feito?
--- API com ASP.NET Core 3.1, utilizando C#, ORM para conexão com banco de dados e Swagger para documentação da API.


Extensões no VSCode:
- C#
- C# Entensions
- C# XML Documentation Comments
________________________________________________

Introdução a linguagem C#:
- Orientada a Objetos.


No ecossistema .NET existe a solução e dentro da solução os projetos.


- namespace: é um mecanismo que organiza e agrupa tipos (como classes, interfaces, enums, delegados, etc.) em grupos lógicos, permitindo que os nomes dos tipos sejam distintos e evitando conflitos de nomes. Em outras palavras, é uma forma de fornecer um escopo para os tipos.


Declarações de variaveis:
- var: é uma palavra-chave que indica que o tipo da variável será inferido pelo compilador.

________________________________________________

Core Commmand line interface: (CLI): 
Exemplo: dotnet --info
dotnet clean
dotnet restore: restaura os pacotes NuGet
dotnet build
________________________________________________

Instalção de pacores NuGet: gerenciador de pacotes do .NET.

MVC: model, view, controller.
- back e front no projeto.


DDD - Domain Driven Design: projeto orientado a dominio.
- alinhar o código com o negocio
- minimo acoplamento
- independencia de tecnologia


link repositório: https://github.com/mfrinfo/curso_aspnetcore_api

________________________________________________


- Como alterar a versão do AspNetCore em um novo projeto:

global.json:
- informações do SDK.
dotnet --list-sdks: lista os SDKs instalados na maquina.
Exemplo:
{
    "sdk": {
        "version": "3.1.101",
        "rollForward": "latestFeature"
    }
}
obs: colocar a versão do SDK que deseja utilizar.

________________________________________________


Solução Asp .NET Core:
.SLN: é um container com um ou mais projetos relacionados;

- Projetos:


Api.Aplication:  é a API (projeto: web API) (startap)
Api.Domain: é o dominio da aplicação : (class Library)

