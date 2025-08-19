## CT-GT-007: Edição de Tarefa com Sucesso

**Módulo/Funcionalidade:**  Gerenciamento de Tarefa
**Cenário de Teste:** Verificar o comportamento do sistema ao editar uma tarefa
**Pré-condições:** Estar logado na plataforma e ter tarefas cadastradas no perfil

### Passos de Execução:
1.  Acessar dashboard após login.
2.  Clicar no ícone de barra lateral no canto superior esquerdo.
3.  Na barra lateral clicar em 'Entrada'.
4.  Clicar em algum card de tarefa.
5.  No pop-up do card realizar a edição.
6.  Clicar em 'Salvar'

**Caminho alternativo**
1.  Acessar dashboard após login.
2.  Clicar no ícone de barra lateral no canto superior esquerdo.
3.  Na barra lateral clicar em 'Entrada'.
4.  Ao passar o cursor por cima do card da tarefa clicar no ícone de lápis.
5.  Realizar a edição.
6.  Clicar em 'Salvar'

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`

### Resultado Esperado:
* O sistema deve permitir a edição do card.
* O sistem deve mostrar uma mensagem pop-up sinalizando a alteração.

### Status de Execução:
* **Data da Execução:** 19/08/2025
* **Testador:** Pablo Costa
* **Resultado:** FAILED
* **Observações:** O sistema permitiu a edição mas não mostrou mensagem confirmando a alteração.
