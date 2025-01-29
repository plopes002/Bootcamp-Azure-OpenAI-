# Bootcamp Azure OpenAI - Microsoft & DIO

## Introdução

Este repositório documenta o aprendizado e as práticas realizadas durante o Bootcamp de Azure OpenAI promovido pela Microsoft e DIO. O objetivo é compreender e aplicar as funcionalidades do Azure OpenAI, desde a criação de recursos até a interação com diferentes modalidades, incluindo textos, imagens e áudio.

## Objetivos do Bootcamp

O bootcamp cobre os principais conceitos e práticas do Azure OpenAI, permitindo que os participantes:

- Implantem um recurso de Azure OpenAI na nuvem.
- Explore o Azure OpenAI Playground para testar prompts e ajustar modelos.
- Configurem um ambiente de chat eficiente e interativo.
- Aprendam a integrar armazenamento de Blobs e outras fontes de dados para aprimorar as respostas do modelo.

## Fundamentos do Azure OpenAI Playground

O **Playground** é uma ferramenta essencial para testar prompts e configurar parâmetros para obter os melhores resultados. Ele permite experimentação e ajustes em tempo real. Entre os principais conceitos abordados estão:

### Tokenização e Parâmetros

- **Temperatura:** Controla a aleatoriedade das respostas. Valores mais baixos geram respostas mais previsíveis, enquanto valores mais altos resultam em maior criatividade.
- **Top-P:** Define o conjunto de palavras consideradas para a resposta. Valores mais baixos restringem as opções, enquanto valores mais altos ampliam a diversidade de respostas.
- **Tokens Máximos:** Determina o número máximo de tokens que podem ser gerados em uma resposta.
- **Penalidades:** Ajustam a frequência e a repetição de palavras na geração do texto.
- **Sistema de Mensagens:** Estrutura a interação entre usuário e modelo, garantindo coerência e contexto.

## Aplicações Práticas

Durante o bootcamp, os participantes experimentam diversas aplicações reais, como:

- Criar e interagir com um **Blob**, permitindo armazenamento e recuperação de informações.
- Aplicar técnicas de **engenharia de prompts** para melhorar as respostas do modelo.
- Testar a configuração de um **chat via CLI**, tornando as interações mais dinâmicas.
- Explorar a geração de **áudio e imagens** usando IA multimodal.

## System Message e Configuração de Contexto

A **System Message** desempenha um papel fundamental na definição do comportamento do modelo. Ela estabelece o tom e as regras da interação, incluindo:

- Contexto inicial do modelo.
- Instruções e direcionamento para respostas.
- Definição de restrições e estilo de resposta.

### Técnicas de Configuração

- **Zero-Shot:** Sem exemplos fornecidos; o modelo responde apenas com base no prompt.
- **Few-Shot:** Alguns exemplos são dados para direcionar as respostas de maneira mais refinada.

## Criatividade e Controle de Respostas

Os parâmetros de **Temperatura** e **Top-P** são essenciais para equilibrar criatividade e coerência nas respostas:

- **Temperatura 0.0:** Respostas mais determinísticas e diretas.
- **Temperatura 1.0:** Respostas mais variadas e imprevisíveis.
- **Top-P 0.1:** Respostas altamente filtradas e coerentes.
- **Top-P 0.9:** Respostas mais diversificadas e criativas.

Além disso, o controle de penalidades influencia a recorrência de palavras:

- **Frequency Penalty:** Reduz a repetição excessiva de palavras.
- **Presence Penalty:** Penaliza palavras que já apareceram para evitar redundância.

## Multimodalidade: Muito Além do Texto

Os modelos do Azure OpenAI não se limitam a texto. Eles também possibilitam a geração de **imagens e áudio**, ampliando as possibilidades criativas.

### Criação de Imagens com DALL-E

Para obter resultados de qualidade ao gerar imagens, é importante considerar:

- **Clareza:** Ser específico no prompt.
- **Especificidade:** Incluir detalhes como estilo, cor e composição.
- **Contexto:** Adicionar informações relevantes para a cena.
- **Estrutura:** Criar prompts bem organizados e detalhados.
