---
title: Contrato de Nível de Serviço do GitHub Enterprise
redirect_from:
  - /github-enterprise-cloud-addendum/
  - /github-business-cloud-addendum/
  - /articles/github-enterprise-cloud-addendum
versions:
  free-pro-team: '*'
---

**Versão curta:** O GitHub garante um compromisso de 99,8% de tempo de atividade trimestral para o serviço de nuvem do GitHub Enterprise (o “**Nível de Serviço**ou “**SLA**”). Se o GitHub não atender ao SLA, o Cliente terá direito a um crédito de serviço para a conta do Cliente (“**Créditos de Serviço**").

Para definições de cada recurso de serviço (“**Recurso de serviço**”) e para revisar a versão histórica e atual, acesse a [Página de Status do GitHub](https://www.githubstatus.com/). Os termos em maiúsculas usados, mas não definidos neste SLA, têm o significado atribuído ao contrato aplicável do cliente.

## Garantia de tempo de atividade

“**Tempo de atividade**” é a porcentagem do total de minutos possíveis que o Serviço estava disponível em um determinado trimestre. O GitHub compromete-se a manter um tempo de atividade de pelo menos 99,9% para o Serviço. O cálculo do tempo de atividade para cada Recurso de Serviço é descrito abaixo (“**Cálculo de Tempo de Atividade**"). Se o GitHub não atender ao SLA, O cliente terá direito a Créditos de Serviço com base no cálculo abaixo (“**Cálculo de Créditos de Serviço**"). Observe que o tempo de inatividade não afeta todos os clientes ao mesmo tempo ou da mesma forma.

| **Recurso de serviço**                                                         | **Cálculo do tempo de atividade**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | **Definições**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | **Cálculo dos créditos de serviço**                                                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| O **serviço** inclui os recursos de serviço a seguir: <ul><li>Problemas</li><li>Pull Requests</li><li>Operações do Git</li><li>Solicitações da API</li><li>Webhooks</li><li>Pages</li><li>Ações</li><li>Pacotes</li></ul> | (total de minutos em um trimestre do calendário - tempo de inatividade) / total de minutos em um trimestre do calendário                                                                                                                                                                                                                                                                                                                                                                                            | “**Tempo de inatividade**” é um período de tempo em que (a) a taxa de erro excede 5% (cinco por cento) em um dado minuto para qualquer Recurso de Serviço ou (b) o Serviço ficou indisponível conforme determinado por uma combinação de sistemas de monitoramento interno e externo do GitHub.                                                                                                                                                                                                                                        | Uma reivindicação de Serviço Créditos pode ser baseada em qualquer um (não em ambos) dos seguintes cálculos: <ul><li>10% do montante que o Cliente pagou por um recurso de serviço em um trimestre de calendário, em que o tempo de atividade para este recurso de serviço foi inferior ou igual a 99,9%, mas superior a 99,0%. <BR><BR>OU <BR><BR></li><li>25% do montante que o Cliente pagou por um recurso de serviço em um trimestre do calendário, em que o tempo de atividade foi inferior a 99,0%.</li></ul> | |
| **Ações**                                                                      | (Total de Execuções Acionadas – Execuções Indisponíveis) / (Total de Execuções Acionadas) x 100                                                                                                                                                                                                                                                                                                                                                                                                                     | “**Total de execuções acionadas**” é o número total de todas as execuções de ações acionadas pelo Cliente em um trimestre do calendário. <br><br> “**Execuções Indisponíveis**" é o número total de execuções no Total de Execuções Acionadas que não foram executadas em um trimestre da agenda.  Falha ao executar uma execução quando o registro do histórico de ações não capturou nenhuma saída 5 (cinco) minutos após o gatilho ter sido acionado com sucesso.                                                       | Igual ao de acima                                                                                                                      |
| **Pacotes**                                                                    | Tempo de atividade de transferência = mesmo que ações <br> <br> Tempo de atividade de armazenamento = 100% - Taxa média de erro* <br> <br> *O cálculo do tempo de atividade exclui o uso público e as transações de armazenamento que não contam nem para Transações de Armazenamento Total ou Transações com falha de Armazenamento (incluindo falhas de pré-autenticação; falhas de autenticação; tentativas de transações para contas de armazenamento acima das suas cotas prescritas). | “**Taxa de erro**" é o número total de Transações de Falhas de Armazenamento dividido pelas Transações Totais de Armazenamento durante um intervalo de tempo definido (definido atualmente em uma hora). Se as Transações de Armazenamento Total em um determinado intervalo de uma hora for zero, a taxa de erro para esse intervalo será 0%. <br><br> “**Taxa de erro média**” é a soma das taxas de erro por cada hora em um trimestre do calendário dividido pelo número total de horas em um trimestre do calendário. | Igual ao de acima                                                                                                                      |

## Exclusões
São excluídos do Cálculo de Tempo de Atividade as falhas de recursos de serviço resultantes de (i) atos, omissões ou abuso do Serviço, incluindo violações do Contrato; (ii) falha na conexão à internet do Cliente; (iii) fatores fora do controle razoável do GitHub, incluindo eventos de força maior; ou (iv) equipamento do Cliente, serviços ou outra tecnologia.

## Serviço de resgate de crédito
Se o GitHub não atender a este SLA, O cliente só poderá resgatar Créditos de Serviço mediante solicitação por escrito ao GitHub no prazo de 30 (trinta) dias a partir do final do trimestre do calendário. Solicitações por escrito de resgate de Créditos de serviço e Relatórios personalizados mensais ou trimestrais do GitHub Enterprise Cloud devem ser enviados para o [Suporte do GitHub](https://support.github.com/contact).

Os Créditos de Serviço podem assumir a forma de reembolso ou crédito para a conta do cliente, não podem ser trocados por um valor em dinheiro, estão limitados a um máximo de 90 (noventa) dias de serviço pago por trimestre do calendário, exigem que o cliente tenha pago qualquer fatura pendente e que expiram após a rescisão do acordo do Cliente com o GitHub. Os Serviço Créditos são o remédio único e exclusivo para qualquer falha do GitHub em cumprir quaisquer obrigações neste SLA. 