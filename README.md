# 📋 SRE

Repository created for the purpose of sharing knowledge and studies related the SRE. In my opnion, is a DevOps that had right.

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
