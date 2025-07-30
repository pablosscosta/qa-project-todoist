## CT-CAD-003: Tentativa de cadastro com e-mail inválido.
**Módulo/Funcionalidade:** Cadastro de Usuário  
**Cenário de Teste:** Verificar a resposta do sistema utilizando um e-mail inválido.  
**Pré-condições:** Não há pré-condições.  

### Passos de Execução:
1.  Acessar a URL: https://www.todoist.com/pt-BR
2.  Clicar no botão "Comece de graça".
3.  No formulário de cadastro, preencher o campo 'E-mail' com um e-mail inválido (Ex: teste@, teste.com).
4. Preencher o campo 'Senha' com uma senha válida (Ex: SenhaDeTeste123!).
5. Clicar no botão "Continuar" ou equivalente.

### Dados de Teste:
**Cenário 01:**
* **E-mail:** teste@
* **Senha:** SenhaDeTeste123!

**Cenário 02:**
* **E-mail:** teste.com
* **Senha:** SenhaDeTeste123!

### Resultado Esperado:
* O sistema não deve permitir o avanço do cadastro.
* O sistema deve mostrar uma mensagem informando que o e-mail é inválido e o motivo pelo qual o e-mail é considerado inválido.

### Status de Execução:
* **Data da Execução:** 30/07/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:**

  **Cenário 01:** O sistema mostrou a mensagem: "Insira uma parte depois de "@". "teste@" está incompleto.

  **Cenário 02:** O sistema mostrou a mensagem: "Inclua um "@" no endereço de e-mail. "teste.com" está com um "@" faltando."
