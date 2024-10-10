# 💻 resumo-do-lab 🚀

💡 Icones usados: <https://github.com/markdown-templates/markdown-emojis>


Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
---
# <img src="https://img.icons8.com/?size=100&id=akG4VRhAoSii&format=png&color=000000" alt="image" width="40" height="40">  Sobre o GitHub 

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com o projeto


📊 No curso de GitHub, aprendi a seguir o fluxo de trabalho para contribuir com projetos open-source hospedados na plataforma. Abaixo, compartilho algumas anotações importantes:

Fork do repositório: Fazer uma cópia do repositório original para a sua conta no GitHub.
Clone local: Baixar o repositório copiado para o seu computador.
Configuração do upstream: Adicionar o repositório original como "upstream" para manter o repositório local atualizado com as mudanças do projeto principal.
Atualização do repositório local: Utilizar os comandos git pull e git fetch para baixar as mudanças do repositório original.
Criação de uma nova branch: Criar uma branch com um nome específico (incluindo seu nome de usuário) para trabalhar nas alterações sem interferir no código principal.
Criação de um arquivo de perfil: Dentro de uma pasta específica, criar um arquivo em formato Markdown (.md) com informações sobre o seu perfil.
Commit e push: Adicionar as alterações ao "staging", fazer um commit com uma mensagem explicativa e enviar as mudanças para o repositório remoto.
Criação de um Pull Request: Solicitar a incorporação das suas alterações no projeto principal por meio de um Pull Request.

No link <https://github.com/digitalinnovationone/dio-lab-open-source?tab=readme-ov-file> é possível consultar mais detalhes sobre o fluxo mencionado acima, além de guias sobre Markdown e outros utilitários relacionados ao GitHub.

💡 As convenções do Git ajudam a manter um histórico de commits claro e organizado, facilitando a colaboração e a manutenção do código, abaixo algumas mais usadas:

* fix: Correção de um bug.
* feat: Adição de um novo recurso.
* docs: Alterações na documentação.
* style: Alterações de formatação que não afetam o código.
* refactor: Mudanças no código que não corrigem bugs nem adicionam recursos1.


# ☁️ Benefícios da Nuvem Azure 


 Ambiente Virtualizado e Previsibilidade de Custos

Os sistemas em nuvem oferecem um ambiente totalmente virtualizado, onde os recursos de TI podem ser dimensionados de forma flexível conforme as necessidades do negócio. Além disso, com o modelo de pagamento baseado no consumo (pague pelo que usar), as empresas têm maior previsibilidade e controle sobre os custos, pagando apenas pelos recursos efetivamente utilizados.

Alta Disponibilidade
A infraestrutura em nuvem garante alta disponibilidade, mantendo os serviços em operação mesmo diante de falhas ou eventos imprevistos. A arquitetura distribuída e redundante dos provedores de nuvem assegura que os sistemas permaneçam acessíveis, minimizando interrupções e aumentando a confiabilidade.

Acordo de Nível de Serviço (SLA)
Os contratos de Serviço de Nível Acordado (SLA) oferecidos por provedores como a Microsoft garantem níveis específicos de disponibilidade e desempenho. Caso os serviços não atinjam as metas estabelecidas no SLA, o cliente recebe créditos como compensação pela indisponibilidade, assegurando uma relação justa e transparente.

A escalabilidade refere-se à capacidade de ajustar dinamicamente os recursos de acordo com a demanda. Isso significa que, conforme a necessidade, é possível aumentar ou diminuir a capacidade dos sistemas, seja em termos de processamento, memória, armazenamento (como aumentar o tamanho dos discos), ou até o número de servidores. Esse ajuste garante que o ambiente de TI esteja sempre otimizado para a carga de trabalho, sem desperdício de recursos ou falta de capacidade, proporcionando flexibilidade e eficiência operacionais.

Elasticidade refere-se à capacidade de um ambiente de TI ajustar automaticamente os recursos com base na demanda em tempo real. Um exemplo clássico é o ajuste no número de servidores de acordo com o volume de requisições: se o sistema detectar um aumento nas requisições (como X requisições por segundo), ele pode automaticamente provisionar mais servidores ou instâncias para atender a essa carga. Da mesma forma, se o número de requisições diminuir (por exemplo, Y requisições por segundo), o sistema pode reduzir a quantidade de servidores para economizar recursos.

Elasticidade é crucial para manter o desempenho e otimizar custos, garantindo que a infraestrutura seja ajustada conforme as necessidades momentâneas do negócio.

Confiabilidade em sistemas em nuvem refere-se à capacidade de garantir a operação contínua e estável dos serviços, minimizando falhas e interrupções.

Previsibilidade na nuvem permite que as empresas avancem com confiança, tanto em termos de desempenho quanto de custos. No Microsoft Azure, essa previsibilidade é fortalecida pelo Well-Architected Framework, que oferece diretrizes para construir soluções de nuvem otimizadas. Esse framework abrange os seguintes pilares:

* Desempenho: Através da implementação de práticas recomendadas, é possível garantir que os sistemas atendam às demandas de carga com consistência e eficiência, ajustando dinamicamente os recursos conforme necessário.
* Custo: O modelo de pagamento baseado no consumo aliado às estratégias de otimização sugeridas pelo framework assegura que os custos sejam previsíveis e controlados, evitando surpresas orçamentárias.
Assim, o Azure Well-Architected Framework ajuda a equilibrar desempenho e custo, proporcionando uma base sólida para decisões estratégicas em ambientes de nuvem.

🔏 Segurança: A nuvem oferece uma ampla gama de ferramentas de segurança que podem atender às necessidades específicas dos clientes, como criptografia de dados, firewalls, monitoramento de ameaças e controle de acesso. No entanto, é importante lembrar que a responsabilidade pela implementação de muitas dessas ferramentas recai sobre o cliente, especialmente em modelos de serviços como Infraestrutura como Serviço (IaaS).

No modelo IaaS, o provedor de nuvem (como o Microsoft Azure) oferece os recursos físicos, como servidores e armazenamento, mas o controle sobre a segurança dos sistemas operacionais, software instalado, atualizações de patches e manutenção fica sob responsabilidade do cliente. Isso garante maior flexibilidade e controle, permitindo que você personalize e gerencie completamente a segurança do ambiente, mas também requer que as políticas de segurança sejam bem implementadas e gerenciadas ativamente.

Esse modelo é ideal para clientes que buscam controle máximo sobre a segurança, permitindo adaptações específicas às suas necessidades e conformidade regulatória.

No Azure, a governança na nuvem pode ser simplificada e fortalecida, especialmente em relação à segurança e à conformidade. Dependendo do seu modelo operacional, como Plataforma como Serviço (PaaS) ou Software como Serviço (SaaS), as atualizações de software e patches de segurança podem ser aplicados automaticamente. Isso garante que os sistemas estejam sempre atualizados e protegidos contra vulnerabilidades sem a necessidade de intervenção manual.

A gerenciabilidade na nuvem refere-se à facilidade com que as organizações podem administrar e monitorar seus recursos e operações em um ambiente de nuvem. Podemos criar a estrutura de servidores, configurações, claster em nuvem via portal ou linha de comando.


Link: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-cloud-computing/?msockid=31e5b9f57bda6d8b0ee8aa5d7aa36c18



# IaaS (Infrastructure as a Service) - Infraestrutura como Serviço
O que é: O IaaS fornece uma infraestrutura de computação virtualizada pela nuvem, como servidores, armazenamento, rede e sistemas operacionais. É a camada mais básica dos serviços em nuvem, onde você tem mais controle sobre os recursos.

Responsabilidade do usuário: Gerenciar o sistema operacional, o middleware, os dados, as aplicações, etc.

Exemplos no Azure:

* Máquinas Virtuais (Azure Virtual Machines): Você pode criar, configurar e gerenciar máquinas virtuais (VMs), incluindo a escolha do sistema operacional, dimensionamento de CPU, armazenamento, etc.
* Rede Virtual (Azure Virtual Network): Permite que os usuários criem redes privadas em nuvem.
* Armazenamento (Azure Storage): Oferece armazenamento escalável para dados estruturados e não estruturados.
* Vantagens: Flexibilidade e controle total sobre a infraestrutura, sem necessidade de manter hardware físico.

# Componentes de Arquitetura do Azure
O Azure é estruturado para oferecer serviços em uma nuvem distribuída, permitindo a construção, implementação e gerenciamento de aplicativos em larga escala. Esses componentes incluem:

Regiões: São áreas geográficas que contêm um ou mais datacenters. Cada região no Azure oferece serviços específicos e permite o isolamento geográfico dos dados.

Zonas de Disponibilidade: São localizações físicas dentro de uma região. Cada zona é composta por um ou mais datacenters com infraestrutura independente (energia, rede, refrigeração) para garantir alta disponibilidade e redundância de serviços.

Pares de Regiões: São duas regiões emparelhadas dentro da mesma geografia (por exemplo, Brasil Sul e Brasil Sudeste). Isso oferece redundância geográfica e recuperação de desastres, já que os dados são replicados entre as duas regiões.

Regiões Soberanas: Regiões dedicadas que atendem a requisitos de soberania de dados, como o Azure Government (EUA) e o Azure China, onde as regulamentações locais exigem controle estrito sobre os dados.

2. Zonas de Disponibilidade e Datacenters do Azure
As Zonas de Disponibilidade são projetadas para fornecer resiliência a falhas localizadas, oferecendo redundância a nível físico. Cada zona possui:

Energia, resfriamento e rede independentes.
Redundância para garantir que, se uma zona falhar, os serviços possam ser transferidos para outra dentro da mesma região.
Datacenters são as unidades físicas que compõem as zonas e as regiões. Cada região pode ter vários datacenters, mas todos dentro de uma zona de disponibilidade compartilham os mesmos princípios de isolamento físico.

3. Recursos e Grupos de Recursos do Azure
Recursos: Qualquer serviço ou componente que você cria e utiliza no Azure, como VMs, bancos de dados, redes virtuais, etc.
Grupos de Recursos: São contêineres que organizam e agrupam recursos relacionados para facilitar o gerenciamento e a automação. Isso permite que você gerencie os recursos como uma unidade lógica, aplicando políticas, controle de acesso e monitoramento.
4. Assinaturas e Recursos de Gerenciamento
Assinaturas: Unidades de faturamento no Azure que associam um conjunto de recursos a um plano de pagamento. Cada assinatura define limites de serviço, políticas de acesso e orçamentos de custos.
Recursos de Gerenciamento: Incluem ferramentas como o Azure Policy (para aplicar regras) e o Azure Cost Management (para controlar e otimizar custos). Além disso, o Azure Role-Based Access Control (RBAC) é usado para conceder permissões a usuários.
5. Hierarquia de Grupos de Recursos, Assinaturas e Grupos de Gerenciamento
Grupos de Recursos: São a camada mais granular da hierarquia e contêm os recursos de uma assinatura.
Assinaturas: São agrupadas em Grupos de Gerenciamento, que fornecem um nível adicional de organização. Você pode aplicar políticas e controles de acesso em nível de grupo de gerenciamento para controlar várias assinaturas de maneira centralizada.
A hierarquia se organiza da seguinte forma:

Grupos de Gerenciamento (topo): Agrupam várias assinaturas e aplicam políticas e permissões.
Assinaturas: Agrupam recursos dentro de uma única unidade de faturamento.
Grupos de Recursos: Organizam e agrupam os recursos individuais.
Recursos: São os serviços específicos, como VMs, bancos de dados e redes.

# O que é o Microsoft Entra ID?
O Microsoft Entra ID é o serviço de gerenciamento de identidades e acessos baseado em nuvem da Microsoft. Ele oferece:

* Gerenciamento de identidades: Criação, gerenciamento e autenticação de usuários e grupos.
* Autenticação segura: Autenticação multifator (MFA), autenticação condicional e Single Sign-On (SSO).
* Integração com aplicativos: Permite que os usuários acessem * vários aplicativos (locais e em nuvem) com uma única credencial.
* Segurança de identidades: Protege contra acessos não autorizados com políticas de segurança robustas e monitoramento contínuo.
* Gerenciamento de dispositivos: Integração com políticas de segurança de dispositivos.
* Esse serviço é amplamente utilizado em ambientes corporativos para gerenciar o acesso de usuários a recursos e dados, tanto no Azure quanto em outros serviços Microsoft 365.

---