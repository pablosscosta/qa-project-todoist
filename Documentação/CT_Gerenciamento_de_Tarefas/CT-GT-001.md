## CT-GT-001: Adicionar tarefa sem preencher o card

**Módulo/Funcionalidade:**  Gerenciamento de Tarefa
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar criar tarefa sem preencher o card
**Pré-condições:** Estar logado na plataforma

### Passos de Execução:
1.  Acessar dashboard após login.
2.  Clicar no ícone de barra lateral no canto superior esquerdo.
3.  Na barra lateral clicar na função 'Adicionar tarefa'.
4.  Sem preencher o card pop-up clicar no botão 'Adicionar tarefa'

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`

### Resultado Esperado:
* O sistema não deve permitir que o usuário crie a tarefa
* O sistema deve desabilitar a o botão 'Adicionar tarefa' do card pop-up ou mostrar alguma mensagem quando tentar cadastrar a tarefa sem preencher o card

### Status de Execução:
* **Data da Execução:** 19/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema não permitiu cadastrar tarefa. O botão 'Adicionar tarefa' fica desabilitado.
