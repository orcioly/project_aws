# Relatório de Implementação de Serviços AWS

Data: 24/11/2025  
Empresa: Abstergo Industries  
Responsável: Orcioly

## Introdução
Este relatório descreve a implementação de três serviços AWS na Abstergo Industries. A meta foi reduzir custos em áreas que apresentavam gastos altos com infraestrutura tradicional.

## Descrição do Projeto
O trabalho foi dividido em três etapas. Cada uma focou em um ponto de economia direta.

### Etapa 1
- **Amazon S3 Standard IA**  
- Armazenamento de baixo custo para dados menos acessados  
- Migração de arquivos que não precisam de acesso diário, reduzindo despesas de armazenamento quente sem perda de disponibilidade

### Etapa 2
- **AWS Lambda**  
- Execução sob demanda  
- Substituição de tarefas que rodavam em instâncias ligadas o tempo todo por funções acionadas apenas quando necessário

### Etapa 3
- **Amazon Aurora Serverless v2**  
- Banco relacional com ajuste automático de capacidade  
- Troca de instâncias fixas por um banco que ajusta o consumo conforme o uso, reduzindo custos em horários de menor tráfego

## Conclusão
A adoção dos serviços reduziu gastos mensais e simplificou partes da operação. A empresa passa a usar recursos que se ajustam melhor ao uso diário. Recomenda-se acompanhar métricas e revisar configurações periodicamente.

## Anexos
- [Planilha de comparação de custos](./anexos/custos_migracao_abstergo.csv)  
- [Lista dos recursos migrados](./anexos/recursos_migrados_abstergo.pdf)  
- [Guia de acesso aos ambientes](./anexos/guia_acesso_ambientes_abstergo.pdf)

Assinatura do Responsável pelo Projeto:

Orcioly Andrade Alves

