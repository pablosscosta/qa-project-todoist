## CT-REC-002: Tentativa de recuperação com formato de e-mail inválido

**Módulo/Funcionalidade:** Recuperação de Senha
**Cenário de Teste:** Verificar o comportamento do sistema quando tentamos recuperar a senha com e-mail inválido
**Pré-condições:** Estar na tela 'Esqueceu sua senha?'

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Clicar na opção 'Esqueceu sua senha?'
4.  No campo 'E-mail' preencher com e-mail inválido.
5.  Clicar no botão "Redefinir minha senha".

### Dados de Teste:
* **E-mail:** `teste`

### Resultado Esperado:
* O sistema não deve enviar opção de recuperação de senha
* O sistema deve informar que o e-mail é inválido

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema não enviou o link e mostrou a mensagem 'Inclua um "@" no endereço de e-mail. "teste" está com um "@" faltando.
