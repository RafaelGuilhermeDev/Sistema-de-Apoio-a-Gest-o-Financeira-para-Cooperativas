# 💰 Sistema de Apoio à Gestão Financeira para Cooperativas
# Integrantes: Bernardo Cesar, Luana Verdugo e Rafael Henrique

## 📌 Sobre o Projeto

Projeto de banco de dados desenvolvido para auxiliar no controle financeiro de cooperativas, organizando receitas, despesas e informações dos cooperados.

A proposta é facilitar o acompanhamento das movimentações financeiras, o cálculo do saldo e a geração de relatórios, contribuindo para uma gestão mais organizada e transparente.

## 🎯 Objetivos

- Registrar entradas e saídas financeiras.
- Organizar movimentações por categoria.
- Identificar os cooperados envolvidos.
- Calcular o saldo financeiro.
- Facilitar consultas e relatórios.

## 🗂️ Principais Entidades

- **Cooperativa:** organização cuja gestão financeira será acompanhada.
- **Cooperado:** associado vinculado à cooperativa.
- **Movimentação:** registro de cada entrada ou saída financeira.
- **Categoria:** classificação das movimentações, como mensalidades e contas de luz.
- **Forma de Operação:** identifica como o dinheiro foi movimentado, como PIX, dinheiro ou cartão.

## 📋 Regras de Negócio

1. Cada movimentação deve conter valor, data, descrição, categoria e forma de operação.
2. Uma movimentação deve representar uma entrada ou uma saída, nunca ambas.
3. Toda movimentação deve estar associada a uma categoria cadastrada.
4. O saldo deve ser calculado pela diferença entre entradas e saídas.
5. Cada cooperado deve possuir um CPF único no cadastro.

## 🛠️ Tecnologias e Conceitos

- PostgreSQL
- SQL
- Modelagem relacional
- Modelo Entidade-Relacionamento (MER)
- Diagrama Entidade-Relacionamento (DER)
- Chaves primárias e estrangeiras
- Relacionamentos e cardinalidades

## 📚 Propósito

Aplicar conceitos de modelagem e bancos de dados relacionais na construção de uma solução voltada à organização e ao controle financeiro de cooperativas.

**Status:** Em desenvolvimento.
