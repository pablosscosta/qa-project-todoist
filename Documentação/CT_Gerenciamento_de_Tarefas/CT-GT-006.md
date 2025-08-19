## CT-GT-006: Busca de Tarefa por Texto Sem Resultados

**Módulo/Funcionalidade:**  Gerenciamento de Tarefa
**Cenário de Teste:** Verificar o comportamento do sistema ao buscar tarefas por termo inexistente nas tarefas cadastradas
**Pré-condições:** Estar logado na plataforma e não ter tarefas cadastradas com o termo a ser pesquisado

### Passos de Execução:
1.  Acessar dashboard após login.
2.  Clicar no ícone de barra lateral no canto superior esquerdo.
3.  Na barra lateral clicar na função 'Buscar'.
4.  Na barra de pesquisa buscar tarefa por um termo.
5.  Clicar 'Enter'

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`
* **Termo de pesquisa:** `um teste`

### Resultado Esperado:
*  O sistema deve mostrar a mensagem 'Nenhuma tarefa concluída encontrada para “um teste”'.

### Status de Execução:
* **Data da Execução:** 19/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema se comportou como esperado.
