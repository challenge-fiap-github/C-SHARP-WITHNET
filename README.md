# OdontoVision

## Objetivo do Projeto

O projeto **OdontoVision** tem como objetivo reduzir sinistros no setor odontológico, utilizando análise preditiva com **Inteligência Artificial (IA)** para detectar fraudes e padrões de uso indevido dos serviços. Além disso, será implementado um aplicativo de gamificação para incentivar práticas preventivas de saúde bucal. O projeto visa melhorar a eficiência operacional das operadoras de planos odontológicos, reduzir custos com fraudes e consultas desnecessárias, e, ao mesmo tempo, proporcionar uma melhor experiência aos pacientes.

## Escopo

O escopo do projeto abrange o desenvolvimento de uma solução backend utilizando **C#** e uma arquitetura **Clean Architecture**, que servirá como base para futuras comunicações com a IA responsável pela análise preditiva de fraudes. A aplicação será responsável por:

- Processar e validar dados relacionados ao uso de serviços odontológicos.
- Detectar padrões de uso suspeitos que possam indicar fraudes.
- Interagir com o aplicativo de gamificação para incentivar boas práticas de saúde bucal.

## Requisitos Funcionais

- Detectar padrões de uso indevido dos serviços odontológicos.
- Permitir integração com o aplicativo de gamificação via APIs.
- Fornecer dados sobre fraudes para o sistema de análise preditiva de IA.

## Requisitos Não Funcionais

- A aplicação deve ser modular e escalável, facilitando futuras integrações e expansões.
- Utilizar **Clean Architecture** para manter o código desacoplado e fácil de manter.
- Garantir segurança no acesso aos dados e comunicações com APIs externas.

## Desenho da Arquitetura

### Clean Architecture

A aplicação adota a **Clean Architecture**, que permite separar responsabilidades de forma clara entre as diferentes camadas do sistema, garantindo que o código seja modular, fácil de manter e que cada parte do sistema tenha uma única responsabilidade.

### Diagrama de Camadas

- **Domínio**: Contém as regras de negócio e as entidades.
- **Aplicação**: Serviços responsáveis por coordenar as operações de negócio.
- **Infraestrutura**: Interage com bancos de dados e APIs externas.
- **Interface**: Define as interfaces e gateways de entrada e saída.

## Tecnologias Utilizadas

- Linguagem: **C#**
- Framework: **.NET Core**
- Arquitetura: **Clean Architecture**
- Banco de Dados: **SQL Server**
- APIs: Comunicação via **REST APIs**
- Integração com **Inteligência Artificial** para análise preditiva

## Como Contribuir

