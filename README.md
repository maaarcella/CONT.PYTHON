# Sistema de Venda e Controle de Estoque em Python

## Descrição

Este projeto consiste em um sistema de venda e gerenciamento de produtos desenvolvido em Python para execução em terminal. O sistema permite cadastrar produtos, listar os itens disponíveis, excluir registros e realizar vendas, atualizando automaticamente o estoque.

Os dados são armazenados em um arquivo de texto (`produto.txt`), garantindo que as informações permaneçam salvas mesmo após o encerramento do programa. Cada produto possui nome, código, preço e quantidade em estoque.

## Funcionalidades

* Cadastro de novos produtos;
* Validação de códigos duplicados;
* Listagem completa dos produtos cadastrados;
* Exclusão de produtos por linha;
* Registro de vendas;
* Atualização automática do estoque após cada venda;
* Armazenamento permanente dos dados em arquivo texto;
* Tratamento de erros para entradas inválidas.

## Tecnologias Utilizadas

* Python 3
* Biblioteca padrão `os`
* Manipulação de arquivos `.txt`

## Objetivo do Projeto

O principal objetivo deste projeto é aplicar conceitos fundamentais de programação, como estruturas de repetição, funções, listas, dicionários, manipulação de arquivos e tratamento de exceções. Além disso, o sistema simula um pequeno controle de estoque utilizado em estabelecimentos comerciais.

## Como Funciona

Ao iniciar o programa, o usuário visualiza um menu com as seguintes opções:

1. Cadastrar Produto
2. Listar Produtos
3. Excluir Produto
4. Realizar Venda
5. Sair

Todas as alterações realizadas são gravadas automaticamente no arquivo `produto.txt`, garantindo a persistência dos dados.

## Aprendizados

Durante o desenvolvimento deste projeto foram praticados conceitos importantes da linguagem Python, incluindo:

* Criação e utilização de funções;
* Leitura e escrita em arquivos;
* Estruturas condicionais;
* Laços de repetição;
* Dicionários e listas;
* Validação de dados;
* Controle de estoque básico.

## Melhorias Futuras

* Edição de produtos cadastrados;
* Pesquisa por nome ou código;
* Relatórios de vendas;
* Controle de lucro e faturamento;
* Interface gráfica;
* Integração com banco de dados.

Este projeto foi desenvolvido com fins educacionais e representa uma aplicação prática dos conceitos básicos de Python na criação de sistemas de gerenciamento de produtos e estoque.
