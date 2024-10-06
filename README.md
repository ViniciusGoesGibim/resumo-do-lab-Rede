## Computação e Rede

### Serviços de computação do Azure
Os serviços de computação do Azure são uma série de recursos que permitem executar aplicativos e serviços na plataforma de computação em nuvem da Microsoft:

- Máquinas virtuais: Sistemas operacionais que funcionam como computadores completos, mas com os recursos de computação e armazenamento originados da nuvem. 
- Serviço de Aplicativo do Azure: Serviço gerenciado para hospedar aplicativos Web, back-ends de aplicativo móvel, APIs RESTful ou processos empresariais automatizados. 
- Azure Resource Manager: Serviço de implantação e gerenciamento do Azure, que permite criar, atualizar e excluir recursos na conta do Azure. 
- Azure Machine Learning: Serviço de computação em nuvem do Azure. 
- Serviços de IA do Azure: Serviço de computação em nuvem do Azure. 
- Microsoft Copilot no Azure PREVIEW: Serviço de computação em nuvem do Azure. 
- Serviço OpenAI do Azure: Serviço de computação em nuvem do Azure

### Máquinas virtuais do Azure
As Máquinas Virtuais do Azure são um serviço de computação em nuvem da Microsoft que oferece VMs (Virtual Machines) para diferentes tipos de cargas de trabalho. Elas podem ser usadas para: Desenvolvimento e teste de aplicativos, Execução de aplicativos na nuvem, Conectar-se à rede da organização.</br>
As VMs do Azure são oferecidas em vários tipos e tamanhos, e podem ser provisionadas em segundos. Elas suportam sistemas operacionais como Linux e Windows Server, além de SQL Server, Oracle, IBM e SAP.

### Conjuntos de dimensionamento de VMs
Os Conjuntos de Dimensionamento de Máquinas Virtuais (VMSS) do Azure são um recurso que permite criar e gerir um grupo de máquinas virtuais (VMs) com balanceamento de carga.</br>
Os VMSS têm as seguintes vantagens:
- Facilidade de criação e gestão de várias VMs
- Aumento ou diminuição automática do número de instâncias de VM de acordo com a procura ou um horário definido
- Distribuição de VMs através de zonas de disponibilidade ou domínios de falha, o que proporciona elevada disponibilidade e resiliência da aplicação
- Dimensionamento automático da aplicação à medida que a procura de recursos muda
- Funciona em grande escala 

### Conjuntos de disponibilidade de VM
Conjuntos de disponibilidade de VMs são grupos de máquinas virtuais (VMs) que oferecem alta disponibilidade e redundância para aplicativos. As VMs em um conjunto de disponibilidade são alocadas mais próximas umas das outras, o que melhora a latência entre elas.</br> 
Os conjuntos de disponibilidade oferecem isolamento de falhas para muitas falhas possíveis, mas ainda podem ser afetados por falhas de infraestrutura compartilhada, como falhas de rede de datacenter. Para maior confiabilidade, é possível replicar as VMs em várias zonas de disponibilidade.

### Área de Trabalho Virtual do Azure
A Área de Trabalho Virtual do Azure é um serviço de virtualização de aplicativos e área de trabalho que permite que funcionários acessem a área de trabalho do Windows de forma remota e segura.</br> 
A Área de Trabalho Virtual do Azure é uma solução para organizações que já têm experiência com a implementação e gestão de VDI (infraestrutura de área de trabalho virtual). O serviço permite que a equipe trabalhe remotamente de qualquer lugar, como em casa, em viagens, nas instalações do cliente ou no escritório.

### Serviços de contêineres do Azure
Os serviços de contêineres do Azure são ferramentas que permitem criar, implantar, gerenciar e executar aplicativos em contêineres: 
- Armazenamento de Contêineres do Azure: Serviço de gerenciamento de volume para aplicativos de contêiner 
- Azure Container Instances (ACI): Serviço que permite executar contêineres na nuvem sem a necessidade de gerenciar servidores virtuais 
- Azure Container Apps: Serviço que permite executar microsserviços e aplicativos conteinerizados em uma plataforma serverless 
- Azure Container Registry: Registro privado do Docker para gerenciar imagens de contêiner 
- Serviço de Kubernetes do Azure (AKS): Serviço Kubernetes gerenciado para executar aplicativos em contêineres.</br>

Os contêineres são pacotes de software que contêm todos os elementos necessários para serem executados em qualquer ambiente.</br> Com os serviços de contêineres do Azure, os desenvolvedores podem compartilhar software e dependências, reduzir os ciclos de desenvolvimento de software e fornecer código com mais rapidez. 

### Azure Functions
Azure Functions é um serviço de nuvem do Microsoft Azure que permite a execução de códigos em resposta a eventos. Ele é uma ferramenta automatizada que fornece a infraestrutura e os recursos necessários para executar os aplicativos.</br> 
O Azure Functions permite que os desenvolvedores se concentrem no código, na linguagem e nos eventos que desejam monitorar.</br>
A infraestrutura do Azure monitora os eventos e executa o código correspondente. 

### Serviços de Aplicativos do Azure
O Serviço de Aplicativos do Azure é uma plataforma como serviço (PaaS) que permite a criação, implantação e dimensionamento de aplicativos web e de API na nuvem.</br></br>
O Serviço de Aplicativos do Azure oferece as seguintes funcionalidades:
- Criação e hospedagem de aplicativos web, back-ends móveis e APIs RESTful 
- Dimensionamento automático e alta disponibilidade 
- Implantações automatizadas do GitHub, Azure DevOps ou qualquer repositório Git 
- Compatibilidade com Windows e Linux 
- Suporte a linguagens de programação como .NET, .NET Core, Java, Node.js, Python ou PHP 
- Suporte a Containers Docker 
- Integração contínua e entrega contínua (CI/CD) 
- Implantações de tempo de inatividade zero 
- Padrões de segurança e conformidade, incluindo SOC e PCI

### Serviços de rede do Azure
Os serviços de rede do Azure são uma série de serviços que oferecem conectividade, proteção e fornecimento de aplicativos para os recursos do Azure. Alguns dos serviços de rede do Azure são:
#### Rede Virtual do Azure
Permite que recursos do Azure se comuniquem entre si, com a internet e com redes locais. 
#### Gerenciador de Rede Virtual do Azure
Permite agrupar, configurar, implantar e gerenciar redes virtuais globalmente. 
#### WAN Virtual do Azure
Oferece uma interface operacional única, reunindo funcionalidades de rede, segurança e roteamento. 
#### Serviços de IP da Rede Virtual do Azure
Permite a comunicação em uma Rede Virtual do Azure, usando endereços IP públicos e privados. 
#### Gerenciador de tráfego do Azure
Distribui o tráfego de maneira ideal para serviços em todas as regiões globais do Azure.
#### Emparelhamento de rede virtual do Azure 
Permite conectar redes virtuais, mesmo que estejam em regiões diferentes.
#### Gateway de VPN
Os serviços de rede do Azure Gateway VPN permitem enviar tráfego criptografado entre redes virtuais do Azure e locais locais, ou entre redes virtuais do Azure, através da rede Microsoft. 
O Gateway de VPN do Azure utiliza protocolos de segurança padrão do setor, como o IPsec (Internet Protocol Security) e IKE (Internet Key Exchange).
#### ExpressRoute
O Azure ExpressRoute é um serviço de rede da Microsoft que permite a criação de conexões privadas entre a infraestrutura local e os datacenters da Microsoft:
- As conexões do ExpressRoute não passam pela Internet pública. 
- O ExpressRoute permite estabelecer conexões com os serviços em nuvem da Microsoft, como o Microsoft Azure, Microsoft 365 e Dynamics 365. 
- O ExpressRoute oferece dois planos de preços: limitado e de dados ilimitado. 
- O ExpressRoute Direct permite aos clientes se conectar diretamente à rede global da Microsoft. 
- O ExpressRoute Direct oferece conectividade dupla de 100 Gbps. 
- O ExpressRoute Direct oferece isolamento físico para indústrias regulamentadas, como bancos, governos e varejo.

### DNS Azure
O DNS Azure é um serviço de hospedagem de domínios DNS que usa a infraestrutura do Microsoft Azure para resolver nomes. O DNS (Domain Name System) é responsável por traduzir nomes de domínio, como www.amazon.com, para endereços IP, como 192.0.2.44.
O DNS Azure oferece várias funcionalidades, incluindo:
- Hospedagem e resolução de domínios públicos
- Gerenciamento de resolução de DNS em redes virtuais
- Registro automático para VMs
- Resolução de nomes entre o Azure e recursos locais
- Proteção de redes híbridas
- Monitoramento de métricas e alertas DNS
- Integração com outros serviços do Azure 

O DNS Azure permite que os domínios sejam hospedados em zonas públicas ou privadas. As zonas privadas são apenas visíveis para VMs que estão na rede virtual. 
Os domínios e registros do DNS Azure podem ser gerenciados através do portal do Azure, dos cmdlets do Azure PowerShell ou da CLI do Azure.




