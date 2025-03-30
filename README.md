# Criando máquinas Virtuais na Azure

Esse desafio teve como objetivo criar um resumo do que foi apresentado sobre a disponibilidade dos serviços da Azure.

Os serviços possuem um acordo de tempo de inatividade aceitável em diferentes níveis. O SLA (Service Level Agreement) é o nível do acordo de disponibilidade, onde cada nível possui um determinado tempo de inatividade aceitável. Caso o serviço fique indisponível por mais tempo que o garantido, o cliente será ressarcido com créditos para serem utilizados na Azure.

### Tabela com o tempo de inatividade aceitável:
| SLA     | Semana       | Mês           | Ano           |
|---------|--------------|---------------|---------------|
| 99%     | 1,68 horas   | 7,2 horas     | 3,65 dias     |
| 99,9%   | 10,1 minutos | 43,2 minutos  | 8,76 horas    |
| 99,95%  | 5 minutos    | 21,6 minutos  | 4,38 horas    |
| 99,99%  | 1,01 minutos | 4,32 minutos  | 52,56 minutos |
| 99,999% | 6 segundos   | 25,9 segundos | 5,26 minutos  |

Serviços como as Máquinas Virtuais e Conta de Armazenamento possuem opções de disponibilidade e redundância que definem o tempo de disponibilidade oferecido.
