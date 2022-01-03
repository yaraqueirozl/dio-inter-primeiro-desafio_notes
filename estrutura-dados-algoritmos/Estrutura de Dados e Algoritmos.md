# Estrutura de Dados e Algoritmos

## Aula 01 - Estrutura de dados

Estrutura de Dados é uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta;

Em uma estrutura de dados, devemos saber como realizar um determinado conjunto de operações básicas, como por exemplo:

- Inserir dados
- Excluir Dados
- Localizar um elemento
- Percorrer todos os itens constituintes da estrutura para visualização
- Classificar (ordem numérica, alfabética...)

Principais estrutura de dados:

- Vetores e Matrizes (arrays)
- Registro
- Lista
- Pilha
- Fila
- Árvore
- Tabela Hash
- Grafos

## Aula 02 - Vetores e Matrizes (Arrays)

## Aula 03 - Registros

Um Registro é uma estrutura que fornece um formato especializado para armazenar informações em memória;

Enquanto Arrays nos permitem armazenar vários dados de um único tipo de dados, o recurso de Registro nos permite armazenar mais de um tipo de dado;

O Registro é composto por campos de dados; Toda estrutura de um registro tem um nome (ex: livro), e seus campos podem ser acessados por meio do uso do operador ponto (.);

Ex: livro.preco

## Aula 04 - Listas

Estrutura de Dados do tipo Lista armazena dados de um determinado tipo em uma ordem específica;

A diferença entre listas e arrays é a de que as listas possuem tamanho ajustável, enquanto arrays possuem tamanho fixo;

Existem dois tipos de listas: ligadas e duplamente ligadas

Lista Ligadas: existem os nós onde cada um dos nós conhece o valor que está sendo armazenado em seu interior, além de conhecer o elemento posterior a ele: por isso ela é chamada de “lista ligada”, pois os nós são amarrados com essa indicação de qual é o próximo nó;

- o último nó é variável

Lista Duplamente Ligada: a grande diferença das listas duplamente ligadas para as listas ligadas é que elas são bidirecionais. Vimos que, naturalmente, não conseguimos “andar para trás” em listas ligadas, pois os nós de uma lista ligada sabem somente quem é o próximo elemento. Nas listas duplamente ligadas, os nós sabem quem é o próximo elemento e também quem é o elemento anterior, o que permite a navegação reversa.

## Aula 05 - pilhas (stack)

estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado;

O acesso aos itens de uma pilha é restrito - somente um item pode ser lido ou removido por vez;

 LIFO ou UEPS: (Last in First Out) (Último que entre e Primeiro que Sai) o primeiro elemento a ser returado é o último que tiver sido inserido;

FIFO ou PEPS: (First in First out) (Primeiro que Entra Primeiro que Sai) o primeiro elemento a ser retirado é o primeiro que tiver sido inserido;

## Aula 06 - Filas

As estruturas de Dados do tipo Fila admite a remoção de elementos e inserção de novos sujeita à seguinte regra de operação: o elemento removido é o que está na estrutura há mais tempo, ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido seguindo o conceito FIFO;

## Aula 07 - árvores

é uma estrutura de dados que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas;

 

## Aula 08 - Tabela Hash (tabela de espalhamento)

Uma tabela hash, de dispersão ou espalhamento é uma estrutura de dados especial, que associa chave de pesquisa a valores;

É uma gerenralização da ideia de array, porém utiliza uma função denominada Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do “array” que define a tabela;

Valores: é a posição ou índice onde o elemento se encontra;

Chaves: parte da informação que compõe o elemento a ser manipulado;

## Aula 09 - grafos

Grafos são estruturas que permitem programa a relação entre objeto;

O objetos são vértices ou “nós” do grafo;

Os relacionamentos são arestas;

Permite fazer qualquer tipo de estrutura com qualquer tipo de pesquisa;