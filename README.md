<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 align="center">📚 Formulário de Registro de Livros</h1>
    <p align="center">
        Um projeto para gerenciamento de livros e clientes, desenvolvido com <strong>ASP.NET Core MVC</strong> e <strong>SQL Azure</strong>. 
        A aplicação oferece funcionalidades completas de CRUD (Create, Read, Update, Delete).
    </p>
    
   <h2>✨ Recursos</h2>
    <ul>
        <li><strong>Criar:</strong> Permite o registro de livros com campos com o Recebedor, Fornecedor, Livro e Data e Hora.</li>
        <li><strong>Ler:</strong> Exibe uma lista de livros registrados em um painel organizado e interativo.</li>
        <li><strong>Atualizar:</strong> Possibilita editar e atualizar as informações dos livros cadastrados.</li>
        <li><strong>Excluir:</strong> Os registros de livros podem ser removidos com facilidade.</li>
    </ul>

   <h2>🛠️ Tecnologias Utilizadas</h2>
    <h3>Back-end</h3>
    <ul>
        <li>ASP.NET Core MVC 8.0</li>
        <li>Entity Framework Core</li>
        <li>SQL Azure</li>
    </ul>

  <h2>📦 Configuração do Projeto</h2>
    <h3>Pré-requisitos</h3>
    <ul>
        <li>.NET SDK 8.0 ou superior</li>
        <li>SQL Azure configurado ou SQL Server local</li>
    </ul>

  <h3>Como executar</h3>
    <ol>
        <li>Clone este repositório: <code>git clone https://github.com/ddouglss/CruedLivro</code></li>
        <li>Navegue até a pasta do projeto e execute os seguintes comandos:</li>
        <pre><code>dotnet restore</code></pre>
        <pre><code>dotnet run</code></pre>
        <li>Acesse a aplicação em <a href="http://localhost:5000" target="_blank">http://localhost:5000</a> ou na porta configurada.</li>
    </ol>

  <h2>📸 Demonstração</h2>
    <p>Abaixo estão algumas capturas de tela da aplicação:</p>
    <ul>
        <li><strong>Tela Inicial:</strong></li>
        <img src="https://github.com/user-attachments/assets/abb4a9b6-11cf-47ac-9e21-10087b84490e" width="600">
        <li><strong>Formulário dos Registros:</strong></li>
        <img src="https://github.com/user-attachments/assets/8e47daf5-1d9e-49cd-b656-0f6550240025" alt="Formulário de Registro de Livros" width="600">
        <li><strong>Painel de Cadastro:</strong></li>
        <img src="https://github.com/user-attachments/assets/9192fa64-9de0-4462-9b0c-e5a298e50775" alt="Painel de Gerenciamento" width="600">
    </ul>
    <p>Substitua <code>path/to/your/image</code> pelo caminho correto das imagens.</p>

   <h2>📂 Estrutura do Projeto</h2>
    <ul>
        <li><strong>API:</strong> Desenvolvida em ASP.NET Core MVC para fornecer endpoints de CRUD.</li>
        <li><strong>Banco de Dados:</strong> Configurado no SQL Azure, com integração via Entity Framework Core.</li>
    </ul>

   <h2>📚 Dependências</h2>
    <pre>
<code>
<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    TargetFramework net8.0 TargetFramework
  </PropertyGroup>
  <ItemGroup>
   PackageReference Include="Microsoft.EntityFrameworkCore" Version="8.0.10" 
    PackageReference Include="Microsoft.EntityFrameworkCore.Design" Version="8.0.10"
      PrivateAssets all PrivateAssets
      IncludeAssets runtime; build; native; contentfiles; analyzers; buildtransitive IncludeAssets
     PackageReference
    PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="8.0.10" 
    PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="8.0.10"
      PrivateAssets all PrivateAssets
      IncludeAssets runtime; build; native; contentfiles; analyzers; buildtransitive IncludeAssets
    PackageReference
  </ItemGroup>
</Project>
</code>
    </pre>

  <h2>📂 Repositório</h2>
    <p>Para acessar o código-fonte, visite o <a href="https://github.com/ddouglss/CruedLivro" target="_blank">repositório no GitHub</a>.</p>

  <h2>📝 Licença</h2>
    <p>Este projeto está licenciado sob os termos da <strong>MIT License</strong>.</p>
    <h2>👤 Autor</h2>
    <p>Este projeto foi desenvolvido por <strong>Douglas Souza Silva</strong>.</p>
    <p>Entre em contato por e-mail: <a href="mailto:ddouglss1999@gmail.com">ddouglss1999@gmail.com</a></p>
</body>
</html>
