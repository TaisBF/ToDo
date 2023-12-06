# ToDo App

Este é um aplicativo de lista de tarefas simples criado em Python usando a biblioteca Flet e SQLite como banco de dados. O aplicativo permite adicionar, marcar como concluída ou incompleta, e visualizar tarefas.

## Pré-requisitos

markdown
- Python 3.x
- [Flet](https://github.com/BecameTrue/flet) - Uma biblioteca para criação de interfaces gráficas simples em Python.
- SQLite - Um banco de dados embutido no Python.

## Instalação

1. Clone ou faça o download deste repositório.
2. Instale as dependências executando:

   ```bash
   pip install flet

# Execução

Execute o aplicativo com o seguinte comando:

  ```bash
  python3 Todo.py
  ```

Certifique-se de ter o Python 3 instalado e acessível no seu ambiente. Se estiver usando um ambiente virtual, ative-o antes de executar o script.

# Funcionalidades

- Adicionar Tarefa: Digite uma tarefa no campo de texto e clique no botão de adição para adicioná-la à lista.
- Marcar como Completa/Incompleta: Use as caixas de seleção ao lado de cada tarefa para marcá-las como completa ou incompleta.
- Filtrar por Status: Use as abas "Todos", "Em andamento" e "Finalizados" para visualizar tarefas com base em seu status.
- 
# Estrutura do Código

- ToDo: Classe principal que define a interface do aplicativo e interage com o banco de dados SQLite.
- db_execute: Função para executar consultas SQL no banco de dados.
- set_value: Atualiza a variável task com o valor do campo de texto.
- add: Adiciona uma nova tarefa ao banco de dados.
- checked: Atualiza o status de uma tarefa (completa/incompleta) no banco de dados.
- tasks_container: Cria um contêiner de tarefas usando a biblioteca Flet.
- update_task_list: Atualiza dinamicamente a lista de tarefas exibida na interface.
- tabs_changed: Atualiza a lista de tarefas com base na aba selecionada.

# Autor
Tais Figueiredo

# Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

JavaScript
Certifique-se de substituir `Todo.py` pelo nome real do seu arquivo Python. Além disso, preencha as informações de autor e licença conforme apropriado para o seu projeto.

