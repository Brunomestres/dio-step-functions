
## Descrição

Este repositório foi criado como parte do desafio da DIO com o objetivo de documentar os conhecimentos adquiridos sobre AWS Step Functions e automação de workflows na AWS.

## Objetivos

* Compreender o funcionamento do AWS Step Functions.
* Criar fluxos de trabalho automatizados.
* Integrar serviços AWS em um processo orquestrado.
* Documentar a experiência prática realizada durante o laboratório.

## O que é o AWS Step Functions?

O AWS Step Functions é um serviço de orquestração que permite coordenar múltiplos serviços da AWS através de fluxos de trabalho visuais.

Com ele é possível criar aplicações distribuídas, automatizar processos e gerenciar estados de execução sem a necessidade de controlar manualmente toda a lógica da aplicação.

## Conceitos Aprendidos

### State Machine

Uma State Machine representa o fluxo de execução da aplicação.

Cada etapa do processo é definida como um estado que pode:

* Executar tarefas
* Tomar decisões
* Aguardar eventos
* Encerrar execuções

### Tipos de Estados

* Task
* Choice
* Wait
* Pass
* Succeed
* Fail

### Benefícios

* Menor complexidade na orquestração
* Monitoramento visual das execuções
* Tratamento de erros integrado
* Escalabilidade automática

## Fluxo Implementado

Fluxo simplificado:

Início → Processamento → Validação → Resultado Final

Durante a execução, cada estado é processado sequencialmente até que o workflow seja concluído com sucesso ou interrompido por alguma falha.

## Execução e Monitoramento

O Step Functions permite acompanhar cada execução em tempo real através do console da AWS, visualizando:

* Estados executados
* Tempo de processamento
* Entradas e saídas
* Possíveis falhas

## Aprendizados

Durante o laboratório foi possível compreender como o AWS Step Functions simplifica a criação de processos automatizados e integrações entre serviços da AWS.

A visualização gráfica dos workflows facilita tanto o desenvolvimento quanto a manutenção de aplicações distribuídas.

## Conclusão

O AWS Step Functions é uma ferramenta poderosa para orquestração de serviços e automação de processos, permitindo criar fluxos robustos, escaláveis e de fácil monitoramento.
