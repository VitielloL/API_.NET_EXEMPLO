# API_.NET_EXEMPLO

Este projeto é uma simples API criada utilizando .NET e Entity Framework Core. Ele se conecta a um banco de dados SQL Server.

## Ferramentas Utilizadas

- [.NET SDK](https://dotnet.microsoft.com/en-us/download)
- [Entity Framework Core CLI](https://learn.microsoft.com/pt-br/ef/core/cli/dotnet)

## Configuração do Ambiente

1. **Instale o .NET SDK**:
    - Baixe e instale o SDK do .NET a partir do [site oficial](https://dotnet.microsoft.com/en-us/download).

2. **Instale o Entity Framework Core CLI**:
    - Siga as instruções disponíveis na [documentação oficial](https://learn.microsoft.com/pt-br/ef/core/cli/dotnet) para instalar a CLI do Entity Framework Core.

## String de Conexão

A string de conexão para o SQL Server foi configurada utilizando as informações disponíveis em [ConnectionStrings.com](https://www.connectionstrings.com/sql-server/).

```json
"ConnectionStrings": {
    "DefaultConnection": "Server=seu_servidor;Database=sua_base_de_dados;User Id=seu_usuario;Password=sua_senha;"
}
