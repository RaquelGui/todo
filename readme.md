# To Do Avançado

Este é um projeto de lista de tarefas avançado desenvolvido em HTML, CSS e JavaScript. Projeto realizado em curso de formação frontend.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Visão Geral

Este projeto consiste em uma aplicação web para gerenciar listas de tarefas. Ele oferece funcionalidades como adicionar, editar, marcar como concluído e excluir tarefas.

## Funcionalidades

-   Adicionar uma nova tarefa
    A função saveTodo() é responsável por criar dinamicamente um novo elemento HTML representando a tarefa e adicioná-lo à lista.

-   Editar uma tarefa existente
    Ao clicar no botão de edição em uma tarefa, o formulário de edição é exibido, permitindo que o usuário altere o texto da tarefa.
    A função toggleForms() é utilizada para alternar entre o formulário de edição e a exibição da lista de tarefas.
    A função updateTodo() atualiza o texto da tarefa no HTML e também atualiza os dados correspondentes no armazenamento local.

-   Marcar uma tarefa como concluída
    Cada tarefa possui um botão de marcação que alterna seu estado entre concluído e não concluído.
    Ao marcar uma tarefa como concluída, sua aparência é alterada e a classe CSS "done" é aplicada para estilização.
    Os dados sobre o estado da tarefa são armazenados no armazenamento local para persistência.

-   Excluir uma tarefa
    Cada tarefa possui um botão de exclusão que permite remover a tarefa da lista.
    Ao clicar no botão de exclusão, a tarefa é removida do HTML e os dados correspondentes são excluídos do armazenamento local.

-   Pesquisar tarefas por nome
    Os usuários podem pesquisar tarefas digitando texto no campo de pesquisa.
    A função getSearchTodos() filtra dinamicamente as tarefas exibidas com base no texto inserido no campo de pesquisa.

-   Filtrar tarefas por estado (todos, feitos, a fazer)
    A função filterTodos() exibe apenas as tarefas que correspondem à opção de filtro selecionada.

    Essas funcionalidades técnicas são implementadas através de eventos JavaScript, manipulação do DOM e interações com o armazenamento local do navegador.

## Estrutura do projeto

'index.html': Arquivo HTML principal que define a estrutura da página.
'css/styles.css': Arquivo CSS que contém estilos para a aplicação.
'js/scripts.js': Arquivo JavaScript que contém a lógica da aplicação.
'img/': Pasta que contém imagens utilizadas na aplicação.

## Contribuições

Contribuições são bem-vindas! 
Para sugestões, correções ou novas funcionalidades, por favor abra uma issue. 

## Autor

@RaquelGui
Sinta-se à vontade para utilizar, modificar e adaptar este conteúdo, de acordo com as necessidades específicas do seu projeto.