## CT-REC-007: Redefinição com sucesso

**Módulo/Funcionalidade:** Recuperação de Senha
**Cenário de Teste:** Verificar comportamento do sistema ao tentar redefinir senha com formato válido.
**Pré-condições:** Estar na tela 'Esqueceu sua senha?'

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Clicar na opção 'Esqueceu sua senha?'
4.  Fornecedor e-mail com formato válido e cadastrado no sistema.
5.  Clicar no botão "Redefinir minha senha".
6.  Acessar a caixa de entrada do email informado e clicar no link.
7.  Na tela 'Redefinir Senha' tentar avançar fornecedo senha com formato válido.

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`

### Resultado Esperado:
* O sistema deve enviar o link de recuperação para o email.
* Na tela de 'Redefinir Senha' o sistema deve permitir a redefinição de senha.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema permitiu a redefinição de senha e mostrou a mensagem 'Sua senha foi alterada e você já está conectado(a)!'
