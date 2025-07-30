## CT-CAD-005: Tentativa de cadastro com e-mail válido e senha em branco

**Módulo/Funcionalidade:** Cadastro de Usuário 
**Cenário de Teste:** Tentativa de cadastro com e-mail válido e campo 'Senha' em branco.  
**Pré-condições:** Ter um e-mail válido.  

### Passos de Execução:
1.  Acessar a URL: https://www.todoist.com/pt-BR
2.  Clicar no botão "Comece de graça".
3.  No formulário de cadastro, preencher o campo 'E-mail' com um e-mail válido.
4.  Não preencher o campo 'Senha' com uma senha válida.
5.  Clicar no botão "Continuar" ou equivalente.

### Dados de Teste:
* **E-mail:** `foyix31279@devdigs.com` (e-mail gerado por um serviço temporário)
* **Senha:** Em branco

### Resultado Esperado:
* O sistema deve impedir o avanço do cadastro.
* O sistema deve exibir uma mensagem informando ao usuário que deve preencher o campo "Senha".

### Status de Execução:
* **Data da Execução:** 30/07/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema exibiu a mensagem: "A senha deve conter no mínimo 8 caracteres"
