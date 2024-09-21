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
