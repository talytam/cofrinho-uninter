<div align="center">

# 🪙 Cofrinho de Moedas

### Projeto acadêmico em Java com conceitos de Programação Orientada a Objetos.

![Ano](https://img.shields.io/badge/projeto-2022-2563EB?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-POO-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

</div>

> **Projeto acadêmico desenvolvido em 2022 durante a graduação na UNINTER.**  
> O repositório foi mantido como registro da minha evolução nos estudos de Java e Programação Orientada a Objetos.

## Sobre o projeto

O sistema simula um **cofrinho de moedas** executado pelo terminal. É possível adicionar, remover e listar valores em diferentes moedas, além de calcular o total convertido para Real.

O exercício foi utilizado para praticar conceitos fundamentais de orientação a objetos.

## Funcionalidades

- adicionar moedas ao cofrinho;
- remover uma moeda pelo tipo e valor;
- listar as moedas armazenadas;
- converter o valor total para Real;
- trabalhar com Real, Dólar e Euro.

> As taxas de conversão utilizadas no código são valores fixos definidos para fins didáticos e não representam cotações atuais.

## Conceitos aplicados

- classes e objetos;
- encapsulamento;
- herança;
- polimorfismo;
- classe abstrata;
- sobrescrita de métodos;
- coleções com `ArrayList`;
- entrada de dados com `Scanner`.

## Estrutura principal

```text
src/
├── module-info.java
└── uninter/
    ├── Principal.java
    ├── Menu.java
    ├── Cofrinho.java
    ├── Moeda.java
    ├── Real.java
    ├── Dolar.java
    └── Euro.java
```

### Organização das classes

- `Moeda`: classe abstrata que define o comportamento comum das moedas.
- `Real`, `Dolar` e `Euro`: especializações de `Moeda`, responsáveis pelas informações e conversões.
- `Cofrinho`: gerencia a coleção de moedas e as operações do cofrinho.
- `Menu`: concentra a interação pelo terminal.
- `Principal`: ponto de entrada da aplicação.

## Como executar

O projeto pode ser importado em uma IDE Java, como Eclipse ou IntelliJ IDEA, e executado a partir da classe:

```text
src/uninter/Principal.java
```

## Contexto

Este é um projeto de aprendizagem desenvolvido em **2022**. Os arquivos compilados não são versionados; o repositório mantém apenas o código-fonte necessário para estudo e execução.

