## CT-GT-002: Adicionar tarefa preenchendo título e descrição

**Módulo/Funcionalidade:**  Gerenciamento de Tarefa
**Cenário de Teste:** Verificar se o sistema permite cadastrado de tarefa preenchendo título e descrição
**Pré-condições:** Estar logado na plataforma

### Passos de Execução:
1.  Acessar dashboard após login.
2.  Clicar no ícone de barra lateral no canto superior esquerdo.
3.  Na barra lateral clicar na função 'Adicionar tarefa'.
4.  No card pop-up preencher título e descrição e clicar no botão 'Adicionar tarefa'

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`
* **Título da tarefa:** `Tarefa teste`
* **Descrição da tarefa:** `Descrição teste`

### Resultado Esperado:
* O sistema deve permitir o cadastro da tarefa.
* O sistema deve mostrar uma mensagem pop-up confirmando o cadastro da tarefa.

### Status de Execução:
* **Data da Execução:** 19/08/2025
* **Testador:** Pablo Costa
* **Resultado:** FAILED
* **Observações:** O sistema permitiu o cadastro da tarefa mas não mostra alguma mensagem confirmando o sucesso do cadastro.
