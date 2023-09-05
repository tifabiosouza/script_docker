# Comandos básicos do docker:

### Docker Compose:
Exemplos:
-   docker-compuse up -d --build
-   docker-compose -f <docker-compose-file-name> -p <project-name> up -d --build

[Help](https://docs.docker.com/compose/reference/#command-options-overview-and-help):

Forma de Usar o comando ````docker compose [OPTIONS]````

````
Opções:
      --ansi string                Controlar quando imprimir caracteres de controle ANSI ("nunca"|"sempre"|"auto") (padrão "auto")
      --compatibility              Execute compose em modo de compatibilidade com versões anteriores
      --env-file stringArray       Especifique um arquivo de ambiente alternativo.
  -f, --file stringArray           Arquivos de configuração composer
      --parallel int               Controle o paralelismo máximo, -1 para ilimitado (padrão -1)
      --profile stringArray        Especifique um profile para ativar
      --project-directory string   Especifique um diretório (nome do grupo que aparece no docker desktop) de trabalho alternativo (padrão: pasta raíz onde o arquivo se encontra)
  -p, --project-name string        Nome do Projeto

Comandos:
  build       Construir ou reconstruir serviços
  config      Analisar, resolver e renderizar arquivo de composição em formato canônico
  cp          Copie arquivos/pastas entre um contêiner de serviço e o sistema de arquivos local
  create      Cria contêineres para um serviço.
  down        Pare e remova contêineres, redes
  events      Receba eventos em tempo real de contêineres.
  exec        Execute um comando em um contêiner em execução.
  images      Listar imagens usadas pelos contêineres criados
  kill        Forçar a parada de contêineres de serviço.
  logs        Ver a saída dos contêineres
  ls          Listar projetos de composição em execução
  pause       Pausar serviços
  port        Imprima a porta pública para uma ligação de porta.
  ps          Listar contêineres
  pull        Baixa imagens
  push        Envia imagens
  restart     Reinicia os serviços
  rm          Remove e para os serviços
  run         Execute um comando único em um serviço.
  start       Inicia serviços
  stop        Para serviços
  top         Mostra os processos em execução
  unpause     Retoma serviços
  up          Cria e inicia containers
  version     Mostra informação da vesrsão do Docker Compose
````
