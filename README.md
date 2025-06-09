# resumo-do-lab
                "Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do Lab na DIO"

                                                     Olá Mundo
                                              Cloud (Nuvem na Internet)
É uma rede de serviços remotos que armazenam e gerenciam dados, executam aplicativos e fornecem conteúdo e serviços. 
Os serviços estão interligados e funcionam como um ecosistema único. Permite aceder aos dados online de qualquer dispositivo com acesso a Internet.
Eistem diferentes tipos de nuvem, como públicas, privadas, híbridas e comunidades. 

                                  Três tipos de forma de consumo de dados e armazenamento. 
* **On-premise (no local):** Modelo baseado para a empresa cuidar da própria infraestrutura física.
  **Vantagem:** Maior controle e personalização.
  **Desvantagens:** Custos altos de manutenção e necessidade de espaço físico.
  
* **Cloud Full (totalmente por nuvem):** Toda a infraestrutura fica em nuvem e o custo é feito pós uso.
  **Vantagem:** custo mais baixo escalabilidade e flexibilidade.
  **Desvantagem:** Dependência da conexão com a Internet.
  
* **Hybrido (parte local e parte Cloud):** Modelo que pode ter servidores físicos como servidores em CLoud.
  **Vantagens:** Flexibilidade de escolher o melhor projeto, inclusive segurança de dados, conforme a necessidade.
  **Desvantagens:** Complexidade na gestão.

                                          Três modelos de computação em nuvem: 
**1. IaaS (Infrastructure as a Service)**
   Resumo: Fornece infraestrutura de TI básica como servidores, armazenamento e redes, via internet. O usúario gerencia o sistema operacional e as aplicações. 
   Exemplos:
   * Amaxon EC2 (AWS)
   * Microsoft Azure Virtual Machines
   * Google Compute Engine. 

**2. PaaS (Platform as a Service)**
   Resumo: Oferece uma plataforma pronta com sistema operacional, banco de dados e ambiente de desenvolvimento. O foco é no desenvolvimento e execução de aplicativoc, sem se proeocupar com a infraestrutura.
   Exemplos:
   * Google APP Engine
   * Microfost Azure App Services
   * Heroku
     
**3. SaaS (Software as a Service)**
    Resumo: Software completo entregue pela internet, acessado via navegador. O provedor cuida de tudo (infraestrutura, plataforma e aplicação)
    Exemplos:
    * Google Workspace (Gmail, Docs, Drive)
    * Microsoft 365 (Outlook, Word, Excel)
    * Salesforce

                                             Responsabilidade Azure (Microsoft)

 O consumidor é responsável pelos dados e pelas informações armazenados na nuvem. (Você não gostaria que o provedor de nuvem pudesse ler suas informações). O consumidor também é responsável pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.
 Com um datacenter local, você é responsável por tudo. Com a computação em nuvem, essas responsabilidades mudam. O modelo de responsabilidade compartilhada está fortemente vinculado aos tipos de serviço de nuvem (abordados posteriormente neste roteiro de aprendizagem): IaaS (infraestrutura como serviço), PaaS (plataforma como serviço) e SaaS (software como serviço). A IaaS coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade. Na outra ponta do espectro, o SaaS coloca a maior parte da responsabilidade no provedor de nuvem. A PaaS, sendo um meio termo entre IaaS e SaaS, situa-se no meio desses dois cenários e distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

O diagrama a seguir destaca como o Modelo de Responsabilidade Compartilhada informa quem é responsável pelo que, dependendo do tipo de serviço de nuvem.

![image](https://github.com/user-attachments/assets/11988119-a0c3-407a-a44c-ca122b692d20)



Ao usar um provedor de nuvem, você sempre será responsável por:

Informações e dados armazenados na nuvem
Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
Contas e identidades das pessoas, serviços e dispositivos em sua organização

**O provedor de nuvem é sempre responsável por:**
 * Datacenter físico
 * Rede física
 * Hosts físicos

**Seu modelo de serviço determinará a responsabilidade por coisas como:**
 * Sistemas operacionais
 * Controles de rede
 * Aplicativos
 * Identidade e infraestrutura


                                                               
   
                                            Benefícios da Nuvem Azure (Microsoft)
      
**ALTA DISPONIBILIDADE →** A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos catrastróficos que possam ocorrer. É totalmente previsto e caso não seja entregue a disponibilidade de utilização, o cliente receberá em credito.
As zonas de disponibilidade, por exemplo, são datacenters fisicamente separados, com infraestrutura independente, que fornecem redundância e alta disponibilidade para os serviços do Azure. Os conjuntos de disponibilidade, por outro lado, permitem que as máquinas virtuais sejam distribuídas por diferentes domínios de falha e atualização, garantindo que, mesmo que um domínio falhe, as máquinas virtuais continuem a funcionar.
Como base **SLA** (Service Level Agreement) "Acordo de Nível de Serviço". É um documento que define os termos e condições de um acordo entre um fornecedor de serviço e um cliente, especificando detalhes como a qualidade, os prazos e as métricas de desempenho.
* **Clareza e transparência:**
Estabelecem as expectativas de forma clara, evitando mal-entendidos e conflitos. 
* **Melhora da qualidade do serviço:**
Fornecem um padrão de referência para a prestação de serviços, o que ajuda a garantir que o cliente esteja satisfeito. 
* **Medição e avaliação de desempenho:**
Permitem que as partes acompanhem o desempenho do fornecedor e identifiquem áreas de melhoria. 
* **Redução de riscos:**
Definem as responsabilidades de cada parte, o que ajuda a reduzir riscos de conflitos e disputas

Tabela de metas comuns de design de disponibilidade de aplicativos que contém exemplos dos tipos de aplicativos que vemos comumente em cada nível de disponibilidade.

![image](https://github.com/user-attachments/assets/d2b01226-13d0-436e-aeb2-4e5505a9f7d4)

**ESCALABILIDADE →** A escalabilidade refere-se à capacidade de ajustar recursos para atender a demanda. A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda, podendo ajustar a capacidade do ambiente para atender uma determinada demanda.
Outro benefício da escalabilidade é que a nuvem é baseada em consumo, ou seja, pagamos apenas oque for consumido, nada além do necessario pelos serviços. Se a demanda cair, podemos  reduzir os recursos e assim reduzir os custos.
Com a escala vertical por exemplo, em um desenvolvimento de um aplicativo precisando de mais capacidade de processamento, é possível escalar verticalmente para adicionar mais CPUs ou RAM a Maquina Virtual. 
* **Tipos de escalabilidade:**
**Escalabilidade vertical (scale-up):** Aumentar os recursos de um único servidor (CPU, RAM, etc.). 
**Escalabilidade horizontal (scale-out):** Adicionar mais servidores para distribuir a carga de trabalho.
  ![image](https://github.com/user-attachments/assets/00fc192b-c596-4886-a8b4-e77ad48ab28e)
 

**ELASTICIDADE →** Com um salto repentino na demanda, os recursos implementados poderão ser plenamente expandidos automaticamente ou manualmente. O mesmo se aplica se houver queda na demanda, os recursos poreão ser reduzidos horizontalmente de forma automatica ou manual.

**Exemplos de uso:**
- Um site de comércio eletrônico pode aumentar a capacidade de computação durante as promoções e reduzi-la após o evento.
- Uma empresa de desenvolvimento de software pode escalar a capacidade de computação para realizar testes e compilações de código durante um projeto intensivo.
- Uma instituição financeira pode aumentar a capacidade de computação durante os horários de pico, quando há maior volume de transações. 
A elasticidade na nuvem é, portanto, um recurso valioso que contribui para a flexibilidade, eficiência e economia das empresas que adotam a computação em nuvem.

![image](https://github.com/user-attachments/assets/762f706d-394e-41fb-8cf7-e02fbdc947e6)

**PREVISIBILIDADE →** A previsibilidade na nuvem permite que avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo _Azure Well-Architected Framewor_ é um conjunto de princípios e ferramentas que ajudam os arquitetos a projetar e construir cargas de trabalho em nuvem de alta qualidade no **Microsoft Azure**. Ele se concentra em cinco pilares principais: Confiabilidade, Otimização de Custos, Excelência Operacional, Eficiência de Desempenho e Segurança. Esses pilares fornecem uma abordagem estruturada para garantir que os aplicativos sejam não apenas funcionais, mas também confiáveis, econômicos, fáceis de gerenciar, eficientes e seguros.

  ![image](https://github.com/user-attachments/assets/0b22f23c-f5bb-4666-b79d-70b51ca3d5a9)

**SEGURANÇA →** A nuvem oferece ferramentas de segurança que atendem as necessidades dos clientes mas é importante ressaltar que a implementação deve ser realizado pelo cliente. As ferramentas de segurança na cloud do Azure são diversas e abrangentes, fornecendo proteção para diversos aspectos da nuvem, desde a segurança das identidades e acessos até a proteção dos dados e infraestrutura. Alguns exemplos incluem o *Microsoft Defender for Cloud*, o *Azure Sentinel*, e o *Azure Information Protection*. 
 **Ferramentas de Segurança do Azure:**
* **Microsoft Defender for Cloud:**
Uma solução unificada que oferece proteção contra ameaças, gerenciamento de segurança e monitoramento de vulnerabilidades em toda a sua infraestrutura na nuvem e localmente. 
* **Azure Sentinel:**
Um sistema de gerenciamento de eventos e informações de segurança (SIEM) e orquestração, automação e resposta (SOAR) que oferece inteligência de ameaças e análise de segurança avançada. 
* **Azure Information Protection (AIP):**
Ajuda a proteger informações sensíveis, classificando, etiquetando e protegendo dados, mesmo quando eles são compartilhados fora da empresa.

 Aqui estão algumas categorias amplas a serem consideradas ao criar um sistema de segurança:
 
 ![image](https://github.com/user-attachments/assets/0b0ae4fb-10d6-416c-8527-dc44f4e08d82)

 **GOVERNANÇAS →** A **auditoria** baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação, refere-se à redução ou minimização dos impactos adversos de um evento ou situação. 
No Azure, as ferramentas de governança incluem serviços que ajudam a controlar e otimizar o uso da nuvem, garantindo conformidade, segurança e eficiência. Algumas dessas ferramentas incluem políticas, alertas, controles de acesso e mecanismos de monitoramento, além de serviços como o Azure Security Center e o Microsoft Purview. 
 **Ferramentas de Governança no Azure:**
* **Políticas do Azure:**
Permitem definir e aplicar regras para recursos do Azure, garantindo conformidade com as normas da organização e regulamentos. 
* **Alertas do Azure:**
Ativam notificações quando determinadas condições são detectadas no ambiente Azure, como desvios de políticas, alertas de segurança ou problemas de desempenho. 
* **Controles de Acesso Baseados em Funções (RBAC):**
Define permissões de acesso aos recursos Azure, restringindo o acesso a usuários e grupos específicos e garantindo que apenas aqueles com permissões necessárias possam acessar e modificar recursos. 
* **Azure Security Center:**
Oferece um painel de controle centralizado para monitorar a segurança do ambiente Azure, identificar ameaças potenciais e responder a incidentes de segurança. 
* **Microsoft Purview:**
Ajuda a catalogar e gerenciar os dados armazenados na nuvem, garantindo que eles estejam em conformidade com as políticas de governança de dados e que estejam disponíveis para aqueles que precisam deles. 
* **Gerenciamento de Custos:**
Permite monitorar e otimizar os gastos com o Azure, identificando oportunidades de redução de custos e garantindo que os gastos estejam alinhados com o orçamento.

![image](https://github.com/user-attachments/assets/fb608140-4dc2-4496-98a7-d00d852b94ff)

**GERENCIABILIDADE →** Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Implementar recursos com base em um modelo pré-configurado, recomendado a necessidade de configuração manual. 
Há dois tipos de capacidade de gerenciamento para computação em nuvem, que podemos incorporar em nossas implantaçõe.

* **Usando APIs**
  No contexto do Azure, as APIs, especialmente através do Azure API Management (APIM), desempenham um papel crucial na gerenciabilidade de serviços e aplicações. O APIM permite publicar, proteger, monitorar e escalar APIs, tornando-as mais fáceis de consumir e gerenciar.
  Em resumo, as APIs, especialmente através do Azure API Management, são um pilar fundamental para a gerenciabilidade de aplicações e serviços no Azure, oferecendo uma solução completa para publicar, proteger, monitorar e escalar APIs.

* **Usando o Power Shell**
  O Azure PowerShell é uma ferramenta poderosa e versátil para gerenciar recursos do Azure. Permite a criação de fluxos de trabalho automatizados e a gestão de recursos usando modelos do Azure Resource Manager. Ele pode ser usado através do Azure Cloud Shell ou instalado localmente no seu computador.
  O Azure PowerShell é uma ferramenta essencial para quem busca automatizar tarefas e gerenciar eficientemente os recursos da Azure Cloud.
  
 ![image](https://github.com/user-attachments/assets/d64d3923-092c-45a6-8acf-b9079f1ae7cb)

                                                        Link Microsoft Azure
                                                        
  [https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/1-introduction-microsoft-azure-fundamentals](url)


                                                       Máquinas Virtuais Azure

![image](https://github.com/user-attachments/assets/b8f90ca9-051b-4a37-bec9-cbcd58bf90d7) Após a criação de uma assinatura Microsoft Azure, podendo ser: 
* **Assinatura Esducacionais:** Assinaturas que oferecem acesso a serviços gerenciados, como o Azure Kubernetes Service (AKS) ou o Azure Container Instances (ACI).
* **Assinatura de Teste Gratuito (Trial):** Uma forma de experimentar os serviços do Azure sem custos iniciais. 
* **Assinaturas Híbridas:** Assinaturas que oferecem acesso a serviços gerenciados, como o Azure Kubernetes Service (AKS) ou o Azure Container Instances (ACI). 

Para iniciar a criação da máquina virtual é nessesário a criação de um grupo de recursos (Azure resource group), refere-se a um agrupamento lógico onde são organizados elementos de dados ou com base em semelhanças ou formando um grupo. Todo recurso criado no Azureprecisa estar atrelado a um resource group.
Sendo importante sempre que possível trabalhar com as mesmas locilidades para que se tenha diminuição na latencia, ou seja, menos atraso na comunicação de dados pela rede.

* **Criação Maquina Virtual:** 
![image](https://github.com/user-attachments/assets/dba5b35b-8f4a-4b1f-a997-88ba769cec3e)

![image](https://github.com/user-attachments/assets/8784a652-2797-46e7-95b8-990bdd2ff027)

![image](https://github.com/user-attachments/assets/15c4cc51-b302-4b66-9578-547e33e8fd7a)

![image](https://github.com/user-attachments/assets/434fecc5-04c0-4baa-a7f3-6c428846325a)

![image](https://github.com/user-attachments/assets/4ea956f2-d218-4610-a1ed-baaacde9299d)

![image](https://github.com/user-attachments/assets/48898d86-11a0-4024-8b71-fd0212fd8035)

![image](https://github.com/user-attachments/assets/eb0b9609-9742-409e-b3c5-5171f82a6222)

![image](https://github.com/user-attachments/assets/723a58df-5287-4bf3-a2d8-546ff9090c5f)

![image](https://github.com/user-attachments/assets/d272c092-6194-420f-9098-338c16a2891f)

![image](https://github.com/user-attachments/assets/5ef33370-85f2-4c9f-acde-bffc057cc06f)

* **Parar Máquina Virtual:**
![image](https://github.com/user-attachments/assets/104c1c5f-fcd7-4beb-a5d4-c37b93920989)

![image](https://github.com/user-attachments/assets/4ee31e2b-217e-4a3c-a54d-5d0588d87a87)

* **Excluir Máquina Virtual**

![image](https://github.com/user-attachments/assets/be3b2f33-826d-42a9-a98f-1d21b8b2a576)

![image](https://github.com/user-attachments/assets/962d39a4-7505-4e06-ab0e-c5fd5ca7162d)

![image](https://github.com/user-attachments/assets/6474d227-166e-43d4-8468-9b4bbbb18760)

* **Verificar Outros Elementos:**
![image](https://github.com/user-attachments/assets/50d1a8f5-5c67-4591-be00-51b61fb7872c)
![image](https://github.com/user-attachments/assets/b1ad993c-01c5-465f-b606-bc10c3687648)


















