<h1 align="center">Docker na Prática</h1>
<!--<div align="center">--!>

**`Docker`**<br><br>
O objetivo deste projeto é ensinar, por meio da prática, como usar docker e ir evoluindo em seu uso.
#
<h3>Uma Breve explicação</h3> 
Antes de surgir o Docker, a tecnologia revolucionária no campo da Infraestrtura de Ti eram as máquinas virtuais (VMs), que virtualizavam o Hardware. Para que ocorra a vitualização, existe umu software chamado Hypervisor, que é o responsável por fazer com que o hardware hospede múltiplas VMs.
<br><br>Desenho estrutura VM:<br>
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
  <b> - Contêineres:</b>
São unidades isoladas de software que incluem tudo o que a aplicação precisa para funcionar, como código, bibliotecas, ferramentas de sistema e tempo de execução.<br>
<b>- Imagens Docker:</b>
São arquivos imutáveis que contêm as instruções para construir um contêiner.<br>
<b>- Docker Engine:</b>
O software que executa e gerencia os contêineres.<br>
<b>- Docker Hub:</b>
Um repositório público onde você pode encontrar e compartilhar imagens Docker.<br>

</p>
 
