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
* Alterar a rotina de CI para executar em qualquer branch e, assim, mesmo durante o desenvolvimento, vamos ter os testes disponíveis.
* Utilizar estratégias de matrizes para executar a rotina em múltiplos sistemas operacionais diferentes, e ajudar a verificar se a aplicação funciona independente do ambiente.
* Alterar a aplicação para ler variáveis de ambiente, permitindo assim configurar a utilização de bancos de dados que não estão na mesma máquina.
* Como organizar as rotinas de CI em vários arquivos, ficando assim mais fácil de modificar e dar manutenção futuramente.
* Preparar o ambiente para criarmos a imagem Docker, buscando e utilizando uma rotina do marketplace do Actions.
* Fazer login em um repositório do Docker, utilizando outra rotina do Actions e acessando o Docker Hub.
* Criar uma imagem Docker automaticamente, usando a rotina de CI e uma nova rotina do marketplace, lembrando que essa rotina precisa de alguns campos de configuração como o context: para a pasta de execução.
* Salvar um arquivo através dos artefatos; assim é possível baixar os arquivos e verificar se a rotina está funcionando como deveria.
* Baixar um artefato salvo, evitando assim ter que repetir processos e gastar tempo desnecessário com coisas que já fizemos, como a compilação.




