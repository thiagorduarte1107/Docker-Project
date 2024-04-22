Aqui está a descrição dos principais comandos do Docker:

docker run: Este comando é usado para criar e iniciar um contêiner a partir de uma imagem especificada. Ele permite que você execute aplicativos encapsulados em contêineres.
docker stop: Utilizado para parar um ou mais contêineres que estão atualmente em execução. Isso envia um sinal SIGTERM e, após um período de carência, um sinal SIGKILL, se o contêiner não parar.
docker start: Comando que permite iniciar contêineres que foram parados ou criados e ainda não foram iniciados.
docker restart: Reinicia contêineres que estão em execução ou parados. Este comando é útil para fazer refresh em contêineres após mudanças de configuração ou atualizações.
docker rm: Remove um ou mais contêineres. Os contêineres precisam estar parados para que possam ser removidos, a menos que você utilize uma flag para forçar a remoção.
docker pause: Pausa todos os processos dentro de um contêiner específico. Isso é útil para temporariamente interromper as atividades de um contêiner sem terminar sua execução.
docker unpause: Despausa os contêineres que foram pausados, permitindo que eles retomem suas operações normais.
docker exec: Executa um novo comando em um contêiner que já está em execução. É comumente usado para interagir com aplicativos que estão rodando dentro de contêineres.
docker ps: Lista todos os contêineres em execução. Você também pode usar variações deste comando para ver todos os contêineres, independentemente de seu estado.
docker pull: Baixa uma imagem ou um repositório de um registro do Docker. Este comando é usado para puxar imagens que posteriormente podem ser utilizadas para criar contêineres.
docker push: Envia uma imagem ou um repositório local para um registro do Docker, como o Docker Hub, tornando-a acessível para outros usuários.
docker images: Lista todas as imagens Docker armazenadas localmente no sistema do usuário. Este comando é útil para ver as imagens que estão disponíveis para criar contêineres.
docker rmi: Remove uma ou mais imagens Docker do sistema local. Isso é útil para limpar imagens que não são mais necessárias.
docker build: Cria uma imagem a partir de um Dockerfile e um "contexto" de construção. O contexto geralmente consiste no conjunto de arquivos no diretório especificado no Dockerfile.
Estes comandos formam a base da maioria das interações com a plataforma Docker, permitindo gerenciar contêineres e imagens de forma eficaz.
