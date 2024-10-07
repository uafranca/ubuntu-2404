Ubuntu: é um sistema operacional de código aberto, construído a partir do núcleo Linux, baseado no Debian. Esta distribuição Linux é desenvolvida pela Canonical Ltd.

Container: costumam ser comparados com máquinas virtuais (VMs). Assim como as máquinas virtuais, os contêineres permitem empacotar o aplicativo com bibliotecas e outras dependências, oferecendo ambientes isolados para executar os serviços de software.

Docker: é um conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados contêineres. Os contêineres são isolados uns dos outros e agrupam seus próprios softwares, bibliotecas e arquivos de configuração.

Portainer: é uma plataforma leve de entrega de serviços para aplicativos em contêineres que pode ser usada para gerenciar ambientes Docker, Swarm, Kubernetes e ACI. Ele foi projetado para ser tão simples de implantar quanto de usar. O aplicativo permite que você gerencie todos os recursos do seu orquestrador (contêineres, imagens, volumes, redes e muito mais) por meio de uma GUI ‘inteligente’ e/ou uma API extensa.

Cloud: Computação em nuvem é um termo coloquial para a disponibilidade sob demanda de recursos do sistema de computador, especialmente armazenamento de dados e capacidade de computação, sem o gerenciamento ativo direto do utilizador.

## **Links Oficiais da Canonical, Ubuntu, Mint, VirtualBOX, Docker e Portainer:**
🔴 Canonical: https://canonical.com/<br>
🔴 Linux Ubuntu: https://ubuntu.com/<br>
🔴 Linux Mint: https://www.linuxmint.com/<br>
🔴 Oracle VirtualBOX: https://www.virtualbox.org/<br>
🔴 Docker: https://www.docker.com/<br>
🔴 Portainer: https://www.ansible.com/

## **Documentação Oficial do Ubuntu Server 24.04.x LTS e demais projetos:**
🔴 Ubuntu Server Guide: https://ubuntu.com/server/docs<br>
🔴 Ubuntu Server Guide FULL-PDF: https://assets.ubuntu.com/v1/f954307f-ubuntu-server-guide.pdf<br>
🔴 Docker: https://docs.docker.com/<br>
🔴 Portainer: https://docs.portainer.io/

# PRIMEIRA ETAPA: INSTALAÇÃO DO UBUNTU SERVER 24.04

## **🤩🤩 Instalação do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX Projeto Bora para Prática 🤩🤩**

Vídeo de instalação do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender a baixar a ISO do Ubuntu Server do site oficial, criar e customizar a máquina virtual no VirtualBOX e fazer a instalação padrão do Ubuntu Server, no próximo vídeo começamos a etapa de configuração.

Conteúdo estudado nessa instalação:<br>
#01_ Download da ISO do Ubuntu Server 24.04.x LTS<br>
#02_ Criação da Máquina Virtual no Oracle VirtualBOX<br>
#03_ Configurações da Máquina Virtual UbuntuWebserver<br>
#04_ Iniciando a Instalação do Ubuntu Server 24.04.x LTS (localizar a ISO)<br>
#05_ Instalação e Configuração do Ubuntu Server 24.04.x LTS<br>
#06_ Acessando o Ubuntu Server pela primeira vez<br>

# SEGUNDA ETAPA: CONFIGURAÇÕES BÁSICAS DO UBUNTU SERVER 24.04

## **🖥️ Configurações BÁSICAS do Ubuntu Server 24.04.x LTS (Noble Numbat) Essentials ANTES DE CONTINUAR O CURSO 🤩🤩**

Vídeo de configurações básicas do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX antes de continuar o curso, nesse vídeo você vai aprender todos os procedimentos básicos para deixar o nosso servidor configurado de forma correta antes de iniciar a implementação do Docker e Portainer.

Seguir os próximos vídeos de:<br>
01 - Atualização do Ubuntu Server<br>
02 - Configuração do Hostname, Hosts e Placa de Rede<br>
03 - Configuração do Locale, Timezone e NTP<br>
04 - Desligar e Reiniciar o Servidor<br>
05 - Habilitando o Ubuntu Pro<br>
06 - Configuração do OpenSSH Server<br>

## **🤩🤩 Atualização do Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de atualização do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para manter o seu servidor Ubuntu sempre atualizado antes de começar a instalar e configurar os principais serviços de rede.

Apt-Get ou Apt A ferramenta de pacote avançada, é uma interface de usuário de software livre que funciona com bibliotecas centrais para lidar com a instalação e remoção de software no Debian e em distribuições Linux baseadas nele.

Conteúdo estudado nessa atualização:<br>
#01_ Atualizando as Listas sources.list do Apt ou Apt-Get no Ubuntu Server<br>
#02_ Verificando todos os pacotes a serem utilizados no Ubuntu Server<br>
#03_ Atualizando todos os software no Ubuntu Server<br>
#04_ Forçando uma atualização completa de todos os software e dependências no Ubuntu Server<br>
#05_ Forçando uma atualização e remoção de software desnecessários no Ubuntu Server<br>
#06_ Removendo pacotes desnecessários no Ubuntu Server<br>
#07_ Fazendo a limpeza dos repositórios locais e pacotes desnecessários no Ubuntu Server<br>
#08_ Limpando o cache local do sources.list no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DAS ATUALIZAÇÕES DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, O PROCEDIMENTO DE ATUALIZAR É O MESMO NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

## **🤩🤩 Configurando a Placa de Rede do Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de configuração da Placa de Rede do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para configurar o Hostname (Novo do Servidor), FQDN (Nome Totalmente Qualificado), tabela de Hosts (Computadores) e configurar a Placa de Rede de modo Estático no Servidor Ubuntu Server e fazer todos os testes de rede antes de iniciar a instalação dos serviços.

Netplan é um utilitário para configurar facilmente a rede em um sistema Linux. Você simplesmente cria uma descrição YAML das interfaces de rede necessárias e o que cada uma deve ser configurada para fazer. A partir desta descrição o Netplan irá gerar toda a configuração necessária para a ferramenta de renderização escolhida.

Hostname: é usado para exibir o nome DNS do sistema e para exibir ou defina seu nome de host ou nome de domínio NIS. O arquivo /etc/hostname armazena as informações de nome de máquina e domínio no formato FQDN (Fully Qualified Domain Name).

FQDN, algumas vezes denominado nome de domínio absoluto, é um nome de domínio que especifica sua localização exata na árvore hierárquica do Domain Name System. Ele especifica todos os níveis de domínio, incluindo, pelo menos, um domínio de segundo nível e um domínio de nível superior.

Hosts: pesquisa de tabela estática para nomes de host, é utilizado quando não temos servidores DNS (Domain Name System) e fazermos o apontamento diretamente no arquivo localizado em /etc/hosts.

Conteúdo estudado nessa configuração:<br>
#01_ Alterando o nome FQDN (Fully Qualified Domain Name) do Ubuntu Server<br>
#02_ Alterando as entradas no arquivo Hosts do Ubuntu Server<br>
#03_ Instalando os principais software de rede no Ubuntu Server<br>
#04_ Verificando informações do Hardware de Rede no Ubuntu Server<br>
#05_ Verificando as informações de Endereços IPv4 no Ubuntu Server<br>
#06_ Alterando as configurações da Placa de Rede do Ubuntu Server<br>
#07_ Aplicando as configurações do Netplan e verificando as informações de Rede do Ubuntu Server<br>
#08_ Acessando a máquina virtual do Ubuntu Server remotamente via SSH<br>

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DAS CONFIGURAÇÕES DA PLACA DE REDE DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

## **🤩🤩 Configurando a Data e Hora do Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de configuração da Data e Hora do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para configurar a localidade (Locale), Zona de Horário (Timezone), Sincronismo de Data Hora com o Protocolo NTP (Network Time Protocol) e configurações manuais de Data, Hora e sincronismo com o Hardware.

Locale é uma combinação de geografia, idioma e cultura. Para entender Localidade, considere a diferença entre os Estados Unidos e o Reino Unido. Ambos compartilham um idioma comum, mas usam unidades de medida completamente diferentes. Os Estados Unidos usam o idioma inglês, mas usam milhas, graus Fahrenheit e galões, enquanto o Reino Unido usa quilômetros, graus Celsius e litros.

Timezone ou fuso horário é uma área que observa um tempo padrão uniforme para propósitos legais, comerciais e sociais. Os fusos horários tendem a seguir os limites entre países e suas subdivisões em vez de seguir estritamente a longitude, porque é conveniente para áreas em comunicação frequente manter o mesmo horário.

O NTP é um protocolo para sincronização dos relógios dos computadores baseado no protocolo UDP sob a porta 123. É utilizado para sincronização do relógio de um conjunto de computadores e dispositivos em redes de dados com latência variável.

O NTP.br tem por objetivo oferecer condições para que os servidores da Internet no Brasil estejam sincronizados com a Horal Legal Brasileira. Para isso foi firmado um acordo entre o Observatório Nacional (ON) e o NIC.br.

Conteúdo estudado nessa configuração:<br>
#01_ Verificando as informações do Locale (Localidade) do Sistema Operacional Ubuntu Server<br>
#02_ Configurando o Locale (Localidade) do Brasil no Sistema Operacional Ubuntu Server<br>
#03_ Verificando as informações do Timezone (Fuso Horário) do Sistema Operacional Ubuntu Server<br>
#04_ Configurando o Timezone (Fuso Horário) de São Paulo no Sistema Operacional Ubuntu Server<br>
#05_ Configurando o Sincronismo de Data e Hora com o Protocolo NTP no Ubuntu Server<br>
#06_ Reinicializar o serviço do Systemd Timesyncd (Sincronismo de Data e Hora) no Ubuntu Server<br>
#07_ Configuração de Data e Hora Manual no Sistema Operacional Ubuntu Server<br>
#08_ Sincronizando Data e Hora do Sistema Operacional com o Hardware (BIOS) no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DAS CONFIGURAÇÕES DO LOCALE E TIMEZONE DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

## **🤩🤩 Desligando e Reiniciando o Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de desligar e reiniciar o Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para desligar ou reiniciar o servidor de forma correta, vai aprender a agendar um agendamento de desligamento ou reinicialização do sistema.

Conteúdo estudado nesse procedimento:<br>
#01_ Desligando e reinicializando o servidor com halt no Ubuntu Server<br>
#02_ Desligando e reinicializando o servidor com poweroff no Ubuntu Server<br>
#03_ Desligando e reinicializando o servidor com init no Ubuntu Server<br>
#04_ Desligando e reinicializando o servidor com reboot no Ubuntu Server<br>
#05_ Desligando e reinicializando o servidor com shutdown no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DE DESLIGAR E REINICIAR DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS FORMAS DE DESLIGAR E REINICIAR É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

## **🤩🤩 Habilitando a Licença Ubuntu Pro Free no Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de configuração da Licença do Ubuntu Pro Free no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para habilitar o suporte ao Ubuntu Pro Free no Ubuntu Server, esse recurso permiti manter o nosso servidor sempre atualizado com os novos patch's de segurança e garante o suporte até 10 anos de uso da plataforma para Canonical.

O Ubuntu Pro é uma versão do Ubuntu oferecida pela Canonical para nuvens públicas, focada em uso empresarial e de produção. Ele é baseado em componentes do Ubuntu, mas vem com um conjunto de serviços adicionais que são ativados prontos para uso. O Ubuntu Pro também fornece Extended Security Maintenance (ESM).

Conteúdo estudado nessa configuração:<br>
#01_ Verificando as Informações do Sistema Operacional Ubuntu Server<br>
#02_ Atualizando o Sistema Operacional Ubuntu Server<br>
#03_ Criando sua conta no Ubuntu One para registrar o Ubuntu Pro no Ubuntu Server<br>
#04_ Criando uma Assinatura do Ubuntu Pro Free para uso Pessoal<br>
#05_ Verificando a versão do Ubuntu Advantage Tools no Ubuntu Server<br>
#06_ Ativando a sua Assinatura do Ubuntu Pro no Ubuntu Server<br>
#07_ Verificando os repositórios de origem das atualizações no Ubuntu Server<br>
#08_ Habilitando outros Serviços do Ubuntu Pro de Atualização<br>
#09_ Atualizando sistema com o suporte do Ubuntu Pro no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DE HABILITAR O UBUNTU PRO NO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

## **🤩🤩 Configuração do OpenSSH Server no Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de configuração do OpenSSH Server no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para configurar o acesso remoto no nosso servidor de forma segura e customizada.

OpenSSH é um conjunto de utilitários de rede relacionado à segurança que provém a criptografia em sessões de comunicações em uma rede de computadores usando o protocolo SSH.

Conteúdo estudado nessa configuração:<br>
#01_ Instalado o OpenSSH no Ubuntu Server;<br>
#02_ Verificando os Status do Serviço do OpenSSH;<br>
#03_ Verificando a Versão do OpenSSH Server e Client;<br>
#04_ Verificando a Porta de Conexão do OpenSSH Server;<br>
#05_ Diretórios e Arquivos de Configuração do OpenSSH;<br>
#06_ Segurança do Arquivo Hosts.Deny do TCPWrappers;<br>
#07_ Segurança do Arquivo Hosts.Allow do TCPWrappers;<br>
#08_ Configuração do Arquivo sshd_config do OpenSSH;<br>
#09_ Configuração do Arquivo issue.net (Banner Login);<br>
#10_ Acessando Remoto via Powershell, PuTTY e Terminal.

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DAS CONFIGURAÇÕES DO OPENSSH SERVER DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

**OBSERVAÇÃO IMPORTANTE: CASO VOCÊ QUEIRA APLICAR A SEGURANÇA AVANÇADA NO SERVIÇO DO OPENSSH SERVER, VEJA O VÍDEO DE CONFIGURAÇÃO FEITA NO CURSO DO CA-CERTIFICATE, NESSE VÍDEO É HABILITADO OS RECURSOS DE CHAVE PRIVADA/PÚBLICA E CONFIGURADO OS LOGS DETALHADO DE CONEXÃO REMOTA.**

## **🤩🤩 Desabilitando o SNAPd e Cloud-Init no Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de desabilitar e remover o SNAPd e Cloud-Init no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para remover o bloquear a instalação acidental do SNAPd e do Cloud-Init, recursos esses que não será utilizado nesse curso e que consome recursos desnecessário do servidor.

Snap foi criado pela Canonical, o formato de empacotamento de arquivos Snap vem instalado no Ubuntu desde a versão 18.04. Ele isola aplicativos do restante do sistema, uma vantagem em segurança, e tem alguns programas exclusivos, mas vários outros sistemas não são nativamente compatíveis, demandando passos extra para isso.

Snapcraft é uma ferramenta de linha de comando poderosa e fácil de usar para criar snaps. Ele ajuda você a: construir e publicar seus snaps na loja Snap. use canais, trilhas e ramificações para controlar com precisão atualizações e lançamentos.

Cloud-init é o método de multidistribuição padrão da indústria para inicialização de instância de nuvem multiplataforma. Ele é suportado por todos os principais provedores de nuvem pública, sistemas de provisionamento para infraestrutura de nuvem privada e instalações bare-metal.

Conteúdo estudado nessa configuração:<br>
#01_ Listando os aplicativos rodando no SNAPd no Ubuntu Server<br>
#02_ Removendo os aplicativos rodando no SNAPd no Ubuntu Server<br>
#03_ Parando e desabilitando o serviço do SNAPd no Ubuntu Server<br>
#04_ Prevenção contra instalação e inicialização do SNAPd no Ubuntu Server<br>
#05_ Parando e desabilitando o serviço do Cloud-Init no Ubuntu Server<br>
#06_ Prevenção contra instalação e inicialização do Cloud-Init no Ubuntu Server<br>
#07_ Verificando os Status de Serviços Rodando no Ubuntu Server<br>
#08_ Reiniciando o Ubuntu Server para Aplicar as mudanças<br>

## **🖥️ Monitoramento do Desempenho de Hardware do Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de monitoramento do desempenho no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para monitorar o desempenho de Processador CPU, Memória RAM, Hard Disk HD e Rede Network utilizando comandos simples sem a necessidade de instalação de sistemas de monitoramento complexo.

O Kernel é o núcleo central de um sistema operacional. Ele atua como uma ponte entre o hardware do computador e o software, gerenciando os recursos do sistema e permitindo que os programas de software interajam com o hardware de forma eficiente e segura.

A CPU (Central Processing Unit), também conhecida como processador, é o componente principal de um computador responsável por executar instruções e processar dados. É frequentemente descrita como o "cérebro" do computador, pois é onde a maioria das operações de cálculo e lógica são realizadas.

A RAM (Random Access Memory), ou Memória de Acesso Aleatório, é um tipo de memória volátil usada em computadores e outros dispositivos eletrônicos para armazenar dados temporariamente enquanto estão sendo processados. Diferente do armazenamento permanente, como discos rígidos ou SSDs, a RAM é muito mais rápida, mas só mantém os dados enquanto o dispositivo está ligado.

HD, sigla para "Hard Disk" ou "Hard Disk Drive" (Disco Rígido em português), é um dispositivo de armazenamento de dados usado em computadores e outros dispositivos eletrônicos. Ele armazena permanentemente os dados, mesmo quando o computador está desligado. O HD é um dos métodos mais tradicionais de armazenamento, sendo usado para guardar sistemas operacionais, aplicativos, documentos, fotos, vídeos, e qualquer outro tipo de dado digital.

Uma Interface de Rede é um componente de hardware ou software que conecta um dispositivo, como um computador, servidor, ou roteador, a uma rede, permitindo que ele se comunique e troque dados com outros dispositivos na mesma rede ou em redes externas. A interface de rede é essencial para o funcionamento de redes de computadores, permitindo a transferência de dados entre dispositivos conectados.

Conteúdo estudado nessa configuração:<br>
#01_ Instalando os aplicativos de monitoramento no Ubuntu Server<br>
#02_ Verificando a versão do Ubuntu Server<br>
#03_ Verificando a versão do Kernel e Uptime no Ubuntu Server<br>
#04_ Verificando o Desempenho do Processador CPU (Central Processing Unit) Ubuntu Server<br>
#05_ Verificando o Desempenho da Memória RAM (Random-Access Memory) Ubuntu Server<br>
#06_ Verificando o Desempenho Disco HD (Hard-Disk) Ubuntu Server<br>
#07_ Verificando o Desempenho Rede (Network) Ubuntu Server<br>
#08_ Estressando o Servidor Ubuntu Server para verificar as mudanças no Gráfico<br>

## **🖥️ Habilitando a Segurança do Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de segurança no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos habilitar e configurar o sistema de firewall UFW (Uncomplicated Firewall) em nosso servidor, criar as regras básicas de liberação de conexão externos e permitir somente de forma limitada e logada todo o acesso remoto via protocolo SSH em nosso servidor.

Uncomplicated Firewall é uma firewall desenhado para ser de fácil utilização. Utiliza uma interface de linha de comandos simple e de fácil entendimento, e usa o iptables como base para a sua configuração. 

O iptables é um programa escrito em C, utilizado como ferramenta para configurar as regras do protocolo de internet IPv4 na tabela de filtragem de pacotes, utilizando vários módulos e o framework do kernel Linux (versão 2.3.15 ou posteiro).

O netfilter é um módulo que fornece ao sistema operacional Linux as funções de firewall, NAT e log dos dados que trafegam na rede de computadores. iptables é o nome da ferramenta do espaço do usuário que permite a criação de regras de firewall e NATs.

O nftables é um subsistema do kernel Linux que fornece filtragem e classificação de pacotes de rede /datagramas/quadros. Ele está disponível desde o kernel Linux 3.13 lançado em 19 de janeiro de 2014. nftables substitui as partes legadas do iptables do Netfilter.

O rsyslog é uma ferramenta de software de código aberto amplamente utilizada em sistemas Unix e similares para o gerenciamento e a transferência de mensagens de log. Ele é uma implementação avançada do protocolo syslog original, oferecendo funcionalidades aprimoradas que atendem às necessidades modernas de monitoramento e análise de logs em ambientes de TI complexos.

TCP Wrapper é um sistema de rede ACL baseado em host, usado para filtrar acesso à rede a servidores de protocolo de Internet em sistemas operacionais do tipo Unix, como Linux ou BSD.

Conteúdo estudado nessa implementação:<br>
#01_ Verificando a Versão e Status do Firewall UFW no Ubuntu Server<br>
#02_ Habilitando (ENABLE) o Firewall UFW no Ubuntu Server<br>
#03_ Verificando o Serviço do UFW no Ubuntu Server<br>
#04_ Configurando as Regras (RULES) de Bloqueio (DENY) padrão (DEFAULT) de Entrada (INCOMING) e Saída (OUTGOING) do UFW no Ubuntu Server<br>
#05_ Configurando o Nível de Log (LOGGING) do UFW no Ubuntu Server<br>
#06_ Liberando (ALLOW) a Entrada (INCOMING) e Saída (OUTGOING) da Interface de Loopback do UFW no Ubuntu Server<br>
#07_ Liberando (ALLOW) as Saídas (OUTGOING) dos Protocolos Básicos no UFW do Ubuntu Server<br>
#08_ Liberando (ALLOW) a Saída (OUTGOING) do Protocolo ICMP do UFW no Ubuntu Server<br>
#09_ Limitando (LIMIT) e Logando Tudo (LOG-ALL) a Conexão de Entrada (INCOMING) do Protocolo SSH do UFW no Ubuntu Server<br>
#10_ Melhorando a Segurança e Logs Detalhados do TCPWrappers no Ubuntu Server<br>
#11_ Testando novamente a conexão com o OpenSSH e Certificado no Ubuntu Server<br>

# TERCEIRA ETAPA: INSTALAÇÃO E CONFIGURAÇÃO DO DOCKER-CE E PORTAINER

## **🤩🤩 Instalação e Configuração do Docker-CE no Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de instalação e configuração do Docker-CE (Container Engine - Community Edition) no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para instalar e configurar o sistema de Containers Docker-CE (Container Engine - Community Edition) em nosso servidor para criar os primeiros cenários de containers e micro-serviços.

O QUE É E PARA QUE SERVER O DOCKER CE: Docker é um conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados contêineres. Os contêineres são isolados uns dos outros e agrupam seus próprios softwares, bibliotecas e arquivos de configuração.

O QUE É E PARA QUE SERVER O DOCKER COMPOSE: Docker Compose é uma ferramenta para executar aplicativos de vários contêineres no Docker definidos usando o formato de arquivo Compose. Um arquivo Compose é usado para definir como um ou mais contêineres que compõem seu aplicativo são configurados. Depois de ter um arquivo Compose, você pode criar e iniciar seu aplicativo com um único comando: docker compose up.

O QUE É E PARA QUE SERVER O DOCKER HUB: Docker Hub é um registro de contêiner criado para desenvolvedores e colaboradores de código aberto encontrarem, usarem e compartilharem suas imagens de contêiner. Com o Hub, os desenvolvedores podem hospedar repositórios públicos que podem ser usados ​​gratuitamente ou repositórios privados para equipes e empresas.

Conteúdo estudado nesse desafio:<br>
#01_ Instalando as Dependência do Docker-CE no Ubuntu Server<br>
#02_ Adicionando a Chave GPG do Docker-CE no Ubuntu Server<br>
#03_ Adicionando o Repositório do Docker-CE no Ubuntu Server<br>
#04_ Atualizando as Lista do Apt com o novo Repositório do Docker-CE no Ubuntu Server<br>
#05_ Instalando o Docker-CE e suas Dependências no Ubuntu Server<br>
#06_ Instalação do Docker Compose no Ubuntu Server<br>
#07_ Verificando o Serviço e Versão do Docker-CE e Compose<br>
#08_ Localização dos Arquivos de Configuração do Docker-CE<br>
#09_ Interface e Endereçamento IPv4 padrão do Docker-CE<br>
#10_ Adicionando o Usuário Local no Grupo Padrão do Docker-CE<br>
#11_ Verificando Informações Detalhadas do Serviço do Docker-CE<br>
#12_ Iniciando um Container de Teste do Docker-CE<br>
#13_ Iniciando um Container de Teste do Ubuntu Bash no Docker-CE<br>
#14_ Verificando as Imagens dos Containers no Docker-CE<br>
#15_ Limpando todas as Imagens, Containers, Volumes e Redes no Docker-CE<br>

## **🤩🤩 Instalação e Configuração do Portainer-CE no Docker-CE do Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de instalação e configuração do Portainer.io (Community Edition) no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para instalar e configurar o sistema de Gerenciamento de Containers Portainer.io (Community Edition) em nosso servidor para criar e gerenciar os containers e micro-serviços de forma fácil.

O QUE É E PARA QUE SERVER O PORTAINER.IO: Portainer Community Edition (CE) é a nossa base. Com mais de meio milhão de usuários regulares, o CE é um poderoso conjunto de ferramentas de código aberto que permite criar e gerenciar facilmente contêineres no Docker, Docker Swarm, Kubernetes e Azure ACI.

Conteúdo estudado nesse desafio:<br>
#01_ Pesquisando o Container do Portainer.io CE no Docker Hub<br>
#02_ Criando o Volume do Portainer.io CE no Docker-CE<br>
#03_ Criando o Container do Portainer.io CE e utilizando o Volume criado no Docker-CE<br>
#04_ Verificando o Status do Container do Portainer.io CE no Docker-CE<br>
#05_ Verificando a Porta de Conexão do Portainer.io no Docker-CE<br>
#06_ Criando o arquivo de Serviço do Portainer.io CE no Ubuntu Server<br>
#07_ Habilitando o Serviço do Portainer.io no Ubuntu Server<br>
#08_ Verificando o Serviço e Versão do Portainer.io no Ubuntu Server<br>
#09_ Liberando a Conexão de Entrada da Porta do Portainer no UFW do Ubuntu Server<br>
#10_ Acessando e configurando o Portainer.io via navegador<br>

# QUARTA ETAPA: COMANDO BÁSICOS DO DOCKER-CE E PORTAINER

## **🤩🤩 Comandos Básicos do Docker-CE no Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de comandos básicos do Docker-CE (Community Edition) no Ubuntu Server 24.04.x LTS, nesse vídeo você vai aprender todos os comandos básicos para pesquisar, criar, iniciar, parar e remover Containers e Imagens no Docker-CE, que é bases para entender como funcionar o Docker e os Container na prática.

Conteúdo estudado nesse desafio:<br>
#01_ Utilizando os comandos Básico de Pesquisa (Search) do Docker-CE e Docker-HUB<br>
#02_ Utilizando os comandos Básicos de Contêiner (Container) e Imagens (Images) no Docker-CE<br>
#03_ Utilizando os comandos Básicos de Contêiner (Container), Execução (Run) e Sair (Exit) no Docker-CE<br>
#04_ Utilizando os comandos Básicos de Contêiner (Container) e Conectar (Attach) no Docker-CE<br>
#05_ Executando (Exec) comandos Remotos no Contêiner (Container) no Docker-CE<br>
#06_ Parando (Stop), Iniciando (Start), Reiniciando (Restart), Pausando (Pause) e Bloqueando (Wait) os Contêiner (Container) no Docker-CE<br>
#07_ Verificando as Estatísticas (Stats), Processos (Top), Logs (Log) e Inspecionando (Inspect) do Contêiner (Container) no Docker-CE<br>
#08_ Removendo (RM) e Limpando (Prune) os Contêiner (Container) no Docker-CE<br>
#09_ Criando (Create), Renomeando (Rename) e Executando (Run) um novo Contêiner (Container) no Docker-CE<br>
#10_ Listando Imagens (Images), Histórico (History), Inspecionando (Inspect) e Removendo (RM) no Docker-CE<br>

## **🤩🤩 Comandos Básicos de CPU e RAM do Docker-CE no Ubuntu Server 24.04.x LTS Projeto Bora para Prática 🤩🤩**

Vídeo de comandos básicos de CPU e RAM do Docker-CE (Community Edition) no Ubuntu Server 24.04.x LTS, nesse vídeo você vai aprender todos os comandos básicos para criar, iniciar, conectar, parar e atualizar as informações dos Container no Docker-CE referente a Processadores (CPU) e Memória RAM.

Conteúdo estudado nesse desafio:<br>
#01_ Criando (Create) os Contêiner (Container) do Ubuntu (Image) no Docker-CE<br>
#02_ Iniciando (Start) os Contêiner (Container) do Ubuntu (Image) no Docker-CE<br>
#03_ Conectando (Attach) nos Contêiner (Container) do Ubuntu (Image) no Docker-CE<br>
#04_ Parando (Stop) e Inspecionando (Inspect) o Contêiner (Container) do Ubuntu (Image) no Docker-CE<br>
#05_ Atualizando (Update) as Configurações de RAM e CPU dos Contêiner (Container) do Ubuntu (Image) no Docker-CE<br>
#06_ Atualizando (Update) as Configurações de RAM e CPU dos Contêiner (Container) em Execução (Run) no Docker-CE<br>
#07_ Criando (Create) Contêiner (Container) com RAM e CPU Customizada no Docker-CE<br>
