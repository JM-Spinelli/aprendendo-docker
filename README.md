<h1 align="center">Docker na Prática</h1>
<!--<div align="center">--!>

**`Docker`**<br><br>
O objetivo deste projeto é ensinar, por meio da prática, como usar docker e ir evoluindo em seu uso.
#
<h3>Uma Breve explicação</h3> 
Antes de surgir o Docker, a tecnologia revolucionária no campo da Infraestrtura de Ti eram as máquinas virtuais (VMs), que virtualizavam o Hardware. Para que ocorra a vitualização, existe umu software chamado Hypervisor, que é o responsável por fazer com que o hardware hospede múltiplas VMs.
<br><br>Arquitetura VM:<br>
<img src="https://github.com/JM-Spinelli/Minhas-Imagens/raw/main/VM.png" width="200">

<b>Pontos postivos:</b>
 - Mais máquinas dentro de um único servidor<br>
 - Economia em Infraestrutura (menos espaço, menos cabeamento, menos Racks, mais economia de energia etc)<br>

<b>Pontos Negativos:</b>
  - Muito preso a tecnologia do Hardware embarcado. Ou seja, sempre melhores memórias, procesadores, discos de armazenamento e placas mãe.<br>
  - Custo com licença de multiplos SO (Sistemas Operacionais)<br>
  - Tempo de boot (inicialização do sistema) e quantidade de armazenamento necessária para alocar o SO<br><br>

<p>&nbsp;O Docker surgiu em 2013 e junto a si trouxe a revolução que até hoje utilizamos. É uma plataforma se software de código aberto que permite construir, testar, executar e implementar em produção aplicações rodando em containers. Assim como as VMs tem o Hypervisor, os containers tem o Docker, que é o software que permite a criação dos containers.<br>
&nbsp;A grande diferenças da VM para o Container, é que o Docker não virtualiza o hardware, mas sim o SO. Ou seja, o Docker pega uma pequena parte do Kernel do SO em que está hospedado e utiliza para criar um micro SO - micro porque invés de ter <b>Gb</b> (como as VMs), tem <b>Mb</b> - tendo uma estrutura significamente menor.<br><br>
<b>O docker é elaborado da seguinte forma:</b><br>
 
  - <b>Contêineres:</b><br>
São unidades isoladas de software que incluem tudo o que a aplicação precisa para funcionar, como código, bibliotecas, ferramentas de sistema e tempo de execução.<br>
 
- <b>Imagens Docker:</b><br>
São arquivos imutáveis que contêm as instruções para construir um contêiner.<br>

- <b>Docker Engine:</b><br>
O software que executa e gerencia os contêineres.<br>

- <b>Docker Hub:</b><br>
Um repositório público onde você pode encontrar e compartilhar imagens Docker.<br><br>

 Arquitetura Docker:<br>
<img src="https://github.com/JM-Spinelli/Minhas-Imagens/blob/main/Arquitetura_docker.png" width="200">
</p>

 <br>Com essa arquitetura, o Docker trouxe diversos benefícios, como:
 - <b>Fácil Portalidade:</b> Muito mais simples de migrar/implantar em divesos ambientes (test, Uat e Prod) e tecnologias (Linux, Windows e Mac)<br>
 - <b>Economia de Recursos:</b> Grande redução no consumo de unidades de armazenamento<br>
 - <b>Implantação rápida:</b> Muito simples no momento de criar, alterar e disponibilizar os ambientes<br><br>
 #
 
 <h2>Conhecendo os comandos</h2><br>
 <p>
O Docker tem diversos comandos, então irei separá-los por categorias.<br><br>
 <b>Principais Comandos CLI</b><br>
  
  - <b>docker build -</b> Constrói uma imagem a partir de um Dockerfile<br>
  - <b> docker run -</b> Comando utilizado para construir um contêiner a partir de uma imagem docker criada<br>
  - <b> docker exec -</b> Comando que permite você interagir com um contêiner em execução (semelhante a acessar um servidor via RDP ou Putty)<br>
  - <b> docker ps -</b> Lista todos os contêiners em execução<br>
  - <b> docker stop -</b> Para um ou mais contêiners em execução<br>
  - <b> docker start -</b> Inicia um ou mais contêiners parados<br>
  - <b> docker rm -</b> Remove um ou mais contêiners<br>
  - <b> docker rmi -</b> Remove uma ou mais imagens docker<br>
  - <b> docker images -</b> Lista imagens docker locais<br>
  - <b> docker pull -</b> Baixa uma imagem docker de um repositório<br>
  - <b> docker push -</b> Envia uma imagem para um repositório<br>
  - <b> docker tag -</b> Cria uma nova tag para uma imagem existente<br>
  - <b> docker logs -</b> exibe os logs de um contêiner<br>
  - <b> docker cp -</b> Copia arquivos ou diretórios entre um contêiner e o sistema de arquivos local<br>
  - <b> docker commit -</b> Cria uma nova imagem a partir de um contêiner modificado<br>
  - <b> docker inspect -</b> Retorna informações detalhadas sobreum objeto docker<br>
  - <b> docker version -</b> Exibe informações sobre a versão do docker (inclusive, muito útili para saber se os pacotes do docker estão instalados no server)<br>
  - <b> docker info -</b> Exibe informações do sistema Docker<br>
  - <b> docker help -</b> Exibe ajuda sobre comandos docker<br><br>


  <b>Comandos de Imagens</b><br>
  
 - <b>docker build -</b> Constrói uma imagem a partir de um Dockerfile<br>
 - <b>docker images -</b> Lista imagens docker locais<br>
 - <b>docker rmi -</b> Remove uma ou mais imagens docker<br>
 - <b>docker tag -</b> Cria uma nova tag para uma imagem existente<br>
 - <b>docker push -</b> Envia uma imagem para um repositório<br>
 - <b>docker pull -</b> Baixa uma imagem docker de um repositório<br>
 - <b>docker save -</b> Salva uma imagem em um arquivo tar.<br>
 - <b>docker load -</b> Carrega uma imagem a partir de um arquivo tar.<br>
 - <b>docker history -</b> Exibe o histórico de uma imagem<br>
 - <b>docker export -</b> Exporta o sistema de arquivos de um contêiner para um arquivo tar·<br>
 - <b>docker import -</b> Cria uma imagem a partir de um arquivo tar.<br>
 

 <b>Comandos de Contêiners</b><br>
 
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>


 <b>Comando de Imagens</b><br>
 
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>
- <b> -</b> <br>




  <b>Comando de Imagens</b><br>

  - <b> -</b> <br>
  - <b> -</b> <br>
  - <b> -</b> <br>
  - <b> -</b> <br>
  - <b> -</b> <br>
  - <b> -</b> <br>
  - <b> -</b> <br>
  





  
 </p>
