# Global Azure Boot Camp 2019 - DevOps - SQL Database
Demo realizada no evento  [Global Azure Boot Camp 2019 - Uberlândia](http://bit.ly/bootcamp2019udia)

![global](https://github.com/sidneyocirqueira/gab2019-uberlandia-devops-sqldb/blob/master/img/logo.jpg)

## Sumário
* [Palestra](#palestra)
* [Integrantes](#integrantes)
* [Pré-Requisitos](#prerequisitos)
* [Instruções](#instrucoes)
* [CI/CD](#ci/cd)
* [Referências](#referencias)

## Palestra
* DevOps for Azure SQL Databases  

## Integrantes
1. [Renan](https://github.com/renanlq) 
2. [Sidney](https://github.com/sidneyocirqueira)

## Pré-Requisitos:
* [Visual Studio 2019](https://visualstudio.microsoft.com/vs/preview/) | [Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/) | [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)

## Instruções
Instruções para execução do projeto:
* Provisionar Ambiente de Azure SQL Database via [ARM Template](https://github.com/sidneyocirqueira/agb2019-uberlandia-devops-sqldb/tree/master/arm) com Power Shell;
* Executar projeto via Visual Studio ou Visual Studio Code: [Solution](https://github.com/sidneyocirqueira/gab2019-uberlandia-devops-sqldb/blob/master/gab2019.sln) |  [SQL Project](https://github.com/sidneyocirqueira/gab2019-uberlandia-devops-sqldb/tree/master/src/gab.Database)

## CI/CD
* Realizar [Build e Release](https://docs.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops) via Azure DevOps

## Referências 
* Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/
* SSDT: https://devblogs.microsoft.com/ssdt/
* SSDT + Visual Studio: https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/SQL-Server-Data-Tools-for-Visual-Studio
* DevOps: https://docs.microsoft.com/en-us/azure/devops/learn/what-is-devops
* Azure DevOps: https://azure.microsoft.com/en-us/services/devops/
* DevOps Using SQL Server: https://www.microsoft.com/en-us/sql-server/developer-get-started/sql-devops/
* Database DevOps: https://azure.microsoft.com/pt-br/resources/videos/connect-2017-database-devops-with-sql-server-data-tools-and-team-services/
* Treinamento DevOps for Databases: https://www.edx.org/course/devops-for-databases-2 
