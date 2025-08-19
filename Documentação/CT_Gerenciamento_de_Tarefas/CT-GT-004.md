## CT-GT-004: Buscar tarefas para um dia sem tarefas cadastradas

**Módulo/Funcionalidade:**  Gerenciamento de Tarefa
**Cenário de Teste:** Verificar o comportamento do sistema ao buscar tarefas para um dia sem tarefas cadastradas
**Pré-condições:** Estar logado na plataforma e saber um dia que não tenha tarefas cadastradas

### Passos de Execução:
1.  Acessar dashboard após login.
2.  Clicar no ícone de barra lateral no canto superior esquerdo.
3.  Na barra lateral clicar na função 'Buscar'
4.  Na barra de pesquisa do card pop-up digitar o dia da semana ou o dia do mês que não tenha tarefa cadastrada
5.  Clicar 'Enter' após digitar o termo de pesquisa.

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`
* **Termo de pesquisa:** `dia 21`
* **Termo de pesquisa:** `amanhã`

### Resultado Esperado:
* O sistema deve mostrar ao usuário que não há resultados de tarefas para o dia pesquisado

### Status de Execução:
* **Data da Execução:** 19/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema informou que não há mensagens para dia buscado. Mas o processo de buscar tarefas por data poderia ser mais intuitivo. Poderia ter um ícone de calendário para escolher uma data específica. Tem uma opção com ícone de calendário seguido de 'Em breve' mas mostra um interface confusa.
