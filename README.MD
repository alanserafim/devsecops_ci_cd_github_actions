## Pipeline de CI/CD em um projeto Go

Conteúdo abordado

* Conceito e prática de integração contínua.
* Usar Docker Compose para criar e gerenciar ambientes de desenvolvimento.
* Executar serviços com docker-compose up e monitorar com docker-compose logs -f.
* Parametrizar configurações com variáveis de ambiente.
* Executar testes automatizados com docker compose.
* Automatizar a pipeline de integração contínua com GitHub Actions.
* Configurar workflows com arquivos YAML em .github/workflows.
* Definir jobs para instalar dependências, executar lint e testes.
* Proteger a branch principal (main) com regras no GitHub.
* Criar e gerenciar pull requests para garantir a qualidade do código.
* Usar ações pré-definidas em workflows do GitHub Actions.
* Importância de passar corretamente as variáveis de ambiente para testes de integração.
* Configurar variáveis de ambiente no GitHub Actions para evitar falhas de conexão com o banco de dados.
* Vincular portas no Docker Compose para a comunicação entre aplicação e banco de dados.
* Configurar variáveis de ambiente com segurança usando GitHub Secrets.
* Configurar o GitHub Actions para compilar projetos Go com go build.
* Usar upload-artifact do GitHub Actions para disponibilizar executáveis compilados.
* Lidar com artefatos em linguagens compiladas e interpretada.
* Importância da integração e entrega contínua para diferentes tipos de linguagens.


