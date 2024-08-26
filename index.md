---
layout: default
title: Desafio de Programação
description: Desafio de Programação para participar do FSLab.
---

# Desafio: Sistema de Gerenciamento de Tarefas

Esse desafio faz parte da 1ª etapa de seleção para participar do FSLab (Laboratório de Fábricas de Software). 

A 2ª etapa será a realização de uma entrevista, no qual o código implementado aqui será explicado para uma banca.

O prazo para entrega do código é 02/09/2024, enviando para o e-mail *fslab.vilhena@ifro.edu.br*. 

O código pode ser escrito em qualquer linguagem de programação e não deve-se utilizar ChatGPT ou afins.


## Desafio

Você foi contratado para criar um pequeno sistema de gerenciamento de tarefas. O sistema será capaz de adicionar, listar, marcar como concluídas e remover tarefas. Seu objetivo é implementar as funcionalidades descritas abaixo.


## Funcionalidades:

* Adicionar tarefa: crie uma função chamada adicionarTarefa(tarefas, novaTarefa), que adiciona uma nova tarefa (representada como uma string) ao array de tarefas.

* Listar tarefas: crie uma função chamada listarTarefas(tarefas) que percorre o array de tarefas e imprime todas as tarefas no console, indicando quais estão concluídas.

* Marcar tarefa como concluída: crie uma função chamada concluirTarefa(tarefas, indice) que marca a tarefa no índice indicado como concluída.

* Remover tarefa: crie uma função chamada removerTarefa(tarefas, indice) que remove uma tarefa do array com base no índice fornecido.

* Exibir menu: crie uma função chamada exibirMenu() que exibe um menu com as seguintes opções:
    - 1 para Adicionar uma nova tarefa.
    - 2 para Listar todas as tarefas.
    - 3 para Concluir uma tarefa.
    - 4 para Remover uma tarefa.
    - 5 para Sair do programa.

* Execução do programa: utilize um loop para que o programa continue rodando até que o usuário selecione a opção de sair (opção 5).


## Regras:

* Cada tarefa deve ser representada por um objeto com as propriedades:
    - descricao: String que descreve a tarefa.
    - concluida: Booleano que indica se a tarefa foi concluída ou não.
* Ao listar as tarefas, as tarefas concluídas devem ser marcadas com um símbolo, por exemplo, [X] para concluídas e [ ] para pendentes.


## Dicas:

* Use arrays para armazenar as tarefas.
* Utilize funções para modularizar o código.
* A função listarTarefas() deve usar um loop para percorrer o array e exibir as tarefas.
* Utilize estruturas de controle (como **if** e **switch**) para definir as ações com base na escolha do usuário.
