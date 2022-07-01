# 📋 SRE

Na minha opinião, SRE é um DevOps que deu certo !

## DevOps

O que é DevOps ? É uma cultura que utiliza práticas e ferramentas para aumentar a capacidade de uma organização de desenvolver e entregar softwares, serviços, aplicativos e demais produtos de tecnologia com alta velocidade, porém, sem pôr em risco a estabilidade.

Benefícios do DevOps

Aumento da velocidade de entrega

DevOps proporciona, por meio de ferramentas, a automação de processos manuais e lentos, contribuindo, assim, para o aumento da frequência e do número de entregas do seu produto. Quanto mais rápido você conseguir entregar, mais rápido identificará possíveis problemas e poderá corrigir os erros com maior agilidade. Além de identificar necessidades do mercado e conseguir entregar de forma mais rápida, você poderá criar uma vantagem competitiva.

Escalabilidade

Com a automatização da infraestrutura, DevOps proporciona a possibilidade de gerenciar sua infraestrutura como código, diminuindo a interferência manual e, consequentemente, o risco. Você passa a escalar seu código de infraestrutura em diversos ambientes, pois aquilo que é igual para todos é replicado, e implantando de forma individual e automática o que é específico. Com processos automáticos, é possível identificar a necessidade de escalar sua infraestrutura de acordo com a demanda, por exemplo: seu software está recebendo mais requisições do que o esperado para a infraestrutura provisionada; identificado o cenário, antes que aconteça o problema, a automação pode, a partir de um alarme, expandir a infraestrutura para atender às requisições.

Velocidade

As equipes que possuem a cultura DevOps têm maior independência, assumindo a responsabilidade ponta a ponta dos produtos e serviços para, então, realizar as entregas e melhorias de forma mais rápida, contribuindo assim para o atingimento de resultados. Com as equipes juntas, ambas estão olhando para o mesmo objetivo, também não é necessário demandar algo de infraestrutura para fora do time, o que poderia levar mais tempo ou espera por priorização.

Colaboração Contínua

A junção das equipes as torna mais eficientes, promovendo a cultura da responsabilidade ponta a ponta e do sentimento de "dono" do que é feito. As equipes de desenvolvimento e sysadmin colaboram juntas, compartilham muitas responsabilidades e acordam seus fluxos de trabalho, como consequência, acontece a redução de processos ineficazes e a economia de tempo.

Confiabilidade

DevOps promove a garantia da qualidade das atualizações de software e alterações de infraestrutura por meio de processos automatizados de testes em diversos níveis, para, assim, aumentar a confiança das entregas e contribuir com a sua velocidade. Os testes são parte fundamental do processo, e são programados para serem executados no decorrer de todo o ciclo.

Segurança

A adoção da cultura DevOps aumenta a segurança por meio de políticas de segurança automáticas, como controles de acesso entre aplicações, permissionamento, autorização e técnicas de gerenciamento de configuração.

Práticas DevOps

Infraestrutura como código

A infraestrutura como código é uma prática que utiliza técnicas de desenvolvimento de código e que permite controle de versão e integração contínua da infraestrutura, por meio de API, para que os desenvolvedores e sysadmins trabalhem com a infraestrutura de modo programático, em vez de instalar e configurar manualmente a infraestrutura. Isso permite que as equipes dentro de uma empresa operem em uma velocidade maior, uma vez que o código da infraestrutura pode ser reaproveitado, e, quando atualizado, replicado para todos os ambientes que utilizam esse trecho de código de infraestrutura.

Arquitetura de microsserviços

A arquitetura de microsserviços representa um conjunto de pequenos serviços que se interligam para construir um sistema. Cada serviço possui um contexto único de negócio, é executado de forma individual e independente e se comunica com outros serviços por meio de uma interface leve, na maioria dos casos baseada em HTTP. Você pode usar diferentes linguagens de programação para construir os microsserviços e implantá-los independentemente, desde que consigam se expor e se comunicar na interface definida entre eles.

Integração Contínua

A integração contínua é uma prática de desenvolvimento que permite a execução dos testes sempre que as alterações de código são enviadas para o repositório central. Os principais objetivos da integração contínua são encontrar e apontar os erros mais rapidamente a cada alteração, consequentemente, melhorar a qualidade do software e reduzir o tempo necessário para validação.

Entrega Contínua

A entrega contínua é uma prática que permite ao desenvolvedor, ao realizar as alterações de códigos, utilizar a integração contínua para realização dos testes necessários e preparar automaticamente as modificações para uma entrega em produção. Quando a integração contínua é implementada adequadamente, os times terão um pacote de entrega confiável pronto para ser implantado a cada alteração ou conjunto de alterações enviadas para o repositório central.

Monitoração, Alarme, Log e Indexação

Realizar logs de informações das aplicações e infraestrutura é essencial para realizar o monitoramento e gerar alarmes. Ao capturar, indexar e analisar os logs gerados pelos aplicativos e pela infraestrutura, é possível entender como as alterações ou atualizações estão afetando o ambiente e seus usuários, o que proporciona mais facilidade na rastreabilidade, fornecendo maior esclarecimento sobre as causas raiz dos problemas. Com os logs indexados, é possível criar <i>dashboards</i>  de acompanhamento real time e programar alarmes de acordo com determinada situação do ambiente.

Comunicação e Colaboração

O aumento da comunicação, colaboração e compartilhamento de experiência é um dos principais aspectos culturais do DevOps. O uso das práticas e ferramentas contribui para as equipes definirem normas culturais sólidas com relação ao compartilhamento de informações e processos de trabalho. Com a unificação das equipes, todos passam a trabalhar juntos, seguindo um objetivo comum.

Estágios e Ferramentas DevOps

![image](https://user-images.githubusercontent.com/22088545/176786958-6969c189-91a7-49ed-b5d8-492e301c78cf.png)

Planejamento (Plan)

Na fase de planejamento, quando os desenvolvedores e sysadmins estão interagindo para estimar e fatiar as atividades necessárias para a entrega, é fundamental a utilização das práticas de agilidade para melhor organização e fluxo das atividades.

Desenvolvimento ou codificação (Code)

Na etapa de desenvolvimento, com as atividades definidas, os times começam a codificação do software e a codificação da infraestrutura como código. Nessa fase, utilizamos o <a href="https://git-scm.com/"><b>Git</b></a>, sistema de controle de versões distribuído, capaz de registrar o histórico de edições de qualquer tipo de arquivo, facilitando que um time trabalhe no mesmo arquivo de código ao mesmo tempo. Para documentar nosso sistema de forma colaborativa, temos o <a href="https://br.atlassian.com/software/confluence"><b>Confluence</b></a>, e utilizamos o <a href="https://br.atlassian.com/software/jira"><b>Jira</b></a> para organizar e acompanhar as atividades do time, garantindo o gerenciamento de todo o ciclo de desenvolvimento em um único lugar, permitindo o link entre atividades, repositório GIT e documentação do Confluence.

Construção (Build)

Com o código desenvolvido, é necessário realizar o processo de construção também conhecido como build, no qual o código e demais dependências do software e da infraestrutura são baixados do repositório central, compilados e fechados em uma versão, que será disponibilizada para os testes. Também é comum, nessa fase, alguns testes básicos já serem realizados e, se não forem aprovados, o processo de build é cancelado. Para essa fase, podemos utilizar ferramentas como <a href="https://maven.apache.org/">Apache Maven</a>, que realiza a automação da compilação do código e gerenciamento das dependências por meio de XML, ou o <a href="https://gradle.org/">Gradle</a>, que se baseia nos conceitos do Apache Maven porém, introduz uma linguagem de domínio específico, baseada em Groovy em vez de XML, permitindo maiores funções programaticamente.

Teste (Test)

Com a aplicação do <b>DevOps</b>  na fase de testes, além dos testes no software, que vão desde testes unitários, a testes de fumaça (<i>smoke test</i>) e integração, regressão e ponta a ponta, também são realizados os testes de infraestrutura. Para o software, é muito comum a utilização do <a href="https://junit.org/junit5/">JUnit</a> para testes unitários de código, e o <a href="https://www.seleniumhq.org/">Selenium</a> para testes que envolvam telas ou fluxos ponta a ponta. Para infraestrutura, temos o <a href="https://testinfra.readthedocs.io/en/latest/">TestInfra</a> para realizar a validação.

DevSecOps

Durante todo o conteúdo, abordamos diversos pontos relacionados a desenvolvimento, testes, implantação, operação e monitoração, porém, algo que não podemos deixar de citar quando falamos sobre DevOps é a segurança.
Muitas vezes, a abordagem sobre segurança só é colocada para discussão após o software chegar à produção, ou depois que ocorre algum problema relacionado à segurança, como vazamento de informações, ataques e demais brechas. Para evitar que o assunto de segurança só seja abordado no final de todo o ciclo, existe um movimento no mercado, conhecido como <i>Shifting Security Left</i> (movendo a segurança para a esquerda, se considerarmos que o ciclo de desenvolvimento começa na esquerda e termina na direita). Para que o assunto “segurança” seja abordado no início de todo o ciclo, temos os DevSecOps. As principais vantagens ao se trabalhar com DevSecOps são:
- Segurança distribuída dentro da organização;
- Disseminação da consciência de segurança dentro dos times;          
- Softwares mais seguros e com maior qualidade;        
- Redução de custo para identificar e resolver um problema de segurança.
              
![image](https://user-images.githubusercontent.com/22088545/176787238-a4e1aae2-c22b-4ed6-a38c-714f0d758708.png)

Pirâmide SRE

![image](https://user-images.githubusercontent.com/22088545/176451929-1f524652-1248-4c32-93f6-a464021d7ee0.png)

## Monitoring

### Observability

Quando falamos neste tema, é importante termos claro quais são os 3 Pilares da Observabilidade.

<img src="https://user-images.githubusercontent.com/22088545/174402427-b7179c2d-53be-4ae1-8f59-e50f53337a29.png" width="450" height="400" />

1. Logs

Os logs são linhas de texto estruturadas e não estruturadas que um sistema produz quando determinados códigos são executados. Em geral, você pode pensar em um log como um registro de um evento que aconteceu em um aplicativo. Os logs ajudam a descobrir comportamentos imprevisíveis e emergentes exibidos por componentes da arquitetura de microsserviços. 
Os arquivos de log fornecem detalhes abrangentes do sistema, como uma falha e a hora específica em que a falha ocorreu. Ao analisar os logs, você pode solucionar problemas de seu código e identificar onde e por que o erro ocorreu. Os logs também são úteis para solucionar problemas de incidentes de segurança em balanceadores de carga, caches e bancos de dados.

2. Métricas

As métricas são uma representação numérica de dados que podem ser usadas para determinar o comportamento geral de um serviço ou componente ao longo do tempo. Elas são formadas por um conjunto de atributos (por exemplo, nome, valor, rótulo e carimbo de data/hora) que transmitem informações sobre SLAs, SLOs e SLIs. As métricas são um valor medido derivado do desempenho do sistema. Você pode reunir métricas sobre tempo de atividade do sistema, tempo de resposta, número de solicitações por segundo e quanta capacidade de processamento ou memória um aplicativo está usando, por exemplo. Normalmente, SREs e engenheiros de operações usam métricas para acionar alertas sempre que um valor do sistema ultrapassa um limite especificado.

3. Rastreamento

O rastreamento fornece contexto para os outros componentes da observabilidade. Por exemplo, você pode analisar um rastreamento para identificar as métricas mais valiosas com base no que está tentando realizar ou nos logs relevantes para o problema que está tentando solucionar.
O rastreamento é mais adequado para depurar e monitorar aplicativos complexos que disputam recursos (por exemplo, thread, disco ou rede) de maneira não trivial. O rastreamento fornece respostas rápidas para as seguintes perguntas em ambientes de software distribuído:
Quais serviços têm código ineficiente ou problemático que deve ser priorizado para otimização?
Como está a saúde e o desempenho dos serviços que compõem uma arquitetura distribuída?
Quais são os gargalos de desempenho que podem afetar a experiência geral do usuário final?

Saiba mais 💡

Observability : Como gerenciar sistemas complexos em produção
https://www.linkedin.com/pulse/observability-como-gerenciar-sistemas-complexos-em-1-coelho-de-sousa/

Observability : Metrics, Tracing e Logging - O Que, Onde e Porque dos incidentes
https://www.linkedin.com/pulse/observability-metrics-tracing-e-logging-o-que-onde-coelho-de-sousa/

SLI - SLO - SLA - Error Budget
https://harness.io/blog/srm/slo-error-budgets/

#### Prometheus

https://medium.com/tech-grupozap/prometheus-monitorando-a-sa%C3%BAde-da-sua-aplica%C3%A7%C3%A3o-bd9b3b63e7b1
