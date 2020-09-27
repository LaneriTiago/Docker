

# Evolução dos container

- Antigamente cada aplicação era hospedada em um servidor específico
Problema: servidores ociosos // solução: virtualização

- Hypervisor: permite a virtualização dos recursos físicos do sistema. Há redução de recursos elétricos e de rede - melhoria dos recursos de infraestrutura.
Problema: memória dedicada aos sistemas operacionais // solução: container

- Container: as aplicações dividem o mesmo sistema operacional e é mais leve que uma máquina virtual.
Pontos positivos: a) limitação do uso de recursos; b) versões específicas; c) é leve

- Docker Engine: Tecnologias de container para prover ferramentas modernas para deployar e rodar aplicações desenvolvida pela Docker Inc. 
- Docker Compose: Define e orquestra múltiplos containers;
- Docker Swarm: ferramenta para colocar multiplos dockers host's para trabalharem juntos em cluster;
- Docker Hub: repositório com mais de 250 mil imagens para os seus containers:
- Docker Machine: ferramenta que permite instalar e configurar em host virtual.


Hardware -> S.O. -> Docker -> Container 1, Container 2... -> App 1, App 2 

