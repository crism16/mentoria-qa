# mentoria-qa
Exercício de BDD

Criação de cenário BDD de um app de lista de tarefas

História do Usuário:

Como um usuário, eu quero ser capaz de gerenciar minha lista de tarefas de forma eficiente, para que eu possa acompanhar e concluir minhas atividades diárias.

1 - Escreva cenários BDD para a história do usuário. Utilize o formato "Dado, Quando, Então" para descrever o comportamento esperado da aplicação.
2 - Escreva casos de teste para cobrir diferentes aspectos da aplicação, incluindo casos positivos e negativos.

Cenários:

1 - Adicionar uma nova tarefa na lista

Dado que dentro da aplicação 
Quando clico no botão “+”
E preencho as informações obrigatórias
Então a tarefa é criada

2- Editar uma tarefa da lista

Dado que dentro da aplicação NOME_APP
E visualizo a  lista de tarefas
Quando faço alterações na tarefa
Então a tarefa é atualizada

3- Excluir uma tarefa da lista

Dado que estou dentro da aplicação NOME_APP
Quando excluo uma tarefa
Então a tarefa deve sumir da lista de tarefas.

4- Observar os detalhes da tarefa

Dado que dentro da aplicação NOME_APP
Quando clico na tarefa que desejo ver o detalhes
Então  visualizo os detalhes da tarefa

5- Editar tarefa e não salvar a alteração

Dado que dentro da aplicação NOME_APP
E edito uma tarefa
Quando NÃO salvo as alterações
Então as alterações não são salvas

6- Escolher a opção “NÃO” quando for confirmar a exclusão e assim, não excluindo a tarefa.

Dado que dentro da aplicação NOME_APP
Quando excluo alguma tarefa
E NÃO confirmo a exclusão
Então a tarefa NÃO é excluída da lista de tarefas.

7- Visualizar as tarefas Não concluídas

Dado que dentro da aplicação NOME_APP
E visualizo a  lista de tarefas
E clico em filtros
Quando escolho a opção “tarefas não concluídas”
Então vejo as tarefas ainda não concluídas

8- Sinalizar como tarefa concluída

Dado que dentro da aplicação NOME_APP
E visualizo a  lista de tarefas
E clico na tarefa que desejo ajustar
Quando clico em “concluir tarefa”
E confirmo a conclusão
Então a tarefa tem seu Status atualizado para “Tarefa concluída”.

9- Visualizar TODAS as tarefas do dia

Dado que dentro da aplicação NOME_APP
Quando visualizo a lista de tarefa
Então visualizo as tarefas do dia.
