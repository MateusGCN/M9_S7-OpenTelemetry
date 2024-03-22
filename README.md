# Relatório de Observabilidade com OpenTelemetry

## Introdução

Este relatório documenta o processo e os aprendizados adquiridos ao seguir o tutorial sobre observabilidade com OpenTelemetry. O tutorial aborda a implementação de práticas de observabilidade em aplicações .NET, utilizando ferramentas como Prometheus para coleta de métricas e visualização em gráficos.

## Tecnologia Utilizada

O projeto utiliza OpenTelemetry uma ferramenta usada para coletar e exibir dados de sistemas para análise de desempenho e monitoramento de aplicações.

### Principais Componentes

- **OpenTelemetry**: Fornece as APIs e SDKs para implementação em código.
- **Prometheus**: Sistema de monitoramento e alerta para coleta de métricas da aplicação.

## Conceitos Aprendidos

Durante a realização do projeto, diversos conceitos foram aprendidos, alguns deles são:

- **Instrumentação**: Processo de adicionar código ao seu aplicativo para gerar dados de monitoração
- **Métricas**: Medidas quantitativas que representam diferentes aspectos do sistema.
- **Logs**: Registros que fornecem contexto e detalhes sobre a execução do aplicativo.

## Implementação e Código

A implementação seguiu as etapas descritas no artigo, com a instrumentação de uma aplicação .NET para observabilidade. Os principais pontos de implementação incluíram:

1. Configuração do projeto para utilizar o SDK do OpenTelemetry.
2. Adição de instrumentação para coleta de dados de telemetria.
3. Configuração do Prometheus para coleta de métricas.

![image](./images/imagen1.png)
