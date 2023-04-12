# docker-simple-httpd
Esse repositório tem um exemplo simples de como criar e configurar um container Apache usando Docker Compose para exibir uma pagina estática.
<br>
<br>
## Docker
Docker é uma plataforma de software que permite empacotar, enviar e executar aplicativos em contêineres virtuais. Ele torna a implantação de aplicativos mais fácil e portátil, permitindo que os desenvolvedores empacotem seus aplicativos em contêineres e os executem em qualquer sistema operacional que suporte o Docker. Além disso, o Docker também simplifica a implantação e gerenciamento de aplicativos em escala, permitindo que você implante e gerencie facilmente vários contêineres em um único host.

## Docker Compose
Docker Compose é uma ferramenta que permite definir e executar aplicativos Docker multi-container. Com o Docker Compose, você pode definir os serviços que compõem seu aplicativo em um arquivo YAML, incluindo as configurações de rede, volumes e variáveis de ambiente necessárias para cada serviço. Depois, você pode usar o comando docker-compose up para iniciar e executar todos os serviços definidos no arquivo YAML.

O Docker Compose simplifica a implantação e gerenciamento de aplicativos multi-container, permitindo que você execute vários contêineres em um único host com configurações de rede e volume compartilhado, e escalabilidade horizontal com apenas alguns comandos. Isso torna o desenvolvimento e a implantação de aplicativos mais fáceis e mais consistentes em diferentes ambientes.<br>
<br>

## Executando
Req: - docker e docker-compose instalados
  
  Para executar o docker-compose.yml basta estar no diretório e digitar:<br>
  ```
  $ docker-compose up -d
  ```
  ( -d é para subir o container em segundo plano )<br>
  <br>
  
  Para parar/desligar o container basta digitar:<br>
  ```
  $ docker-compose down
  ```
  <br>

Este exemplo simples mostra como o Docker e o Docker Compose podem tornar o processo de implantação e gerenciamento de aplicativos mais ágil, eficiente e escalável, especialmente para aplicativos multi-container. O Docker Compose permite definir e executar aplicativos Docker com vários contêineres em um único host, simplificando a configuração de rede, volumes e variáveis de ambiente.
