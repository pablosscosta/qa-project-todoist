## CT-REC-001: Tentativa de recuperação de senha sem informar e-mail

**Módulo/Funcionalidade:**  Recuperação de Senha
**Cenário de Teste:** Verificar o comportamento do sistema quando o usuário tenta recuperar senha sem preencher o e-mail na tela 'Esqueceu sua senha?'.
**Pré-condições:** Estar na tela 'Esqueceu sua senha?'

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Clicar na opção 'Esqueceu sua senha?'
4.  No campo 'E-mail' deixar em branco
5.  Clicar no botão "Redefinir minha senha".

### Dados de Teste:
* **E-mail:** Em branco

### Resultado Esperado:
* O sistema não deve enviar opção de recuperação de senha pois não foi fornecido e-mail.
* O sistema deve mostrar alguma mensagem orientando o usuário.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema mostrou ao usuário 'Insira um endereço de e-mail válido.'
