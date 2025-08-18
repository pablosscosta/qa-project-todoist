## CT-REC-003: Tentativa de Recuperação com E-mail Não Cadastrado

**Módulo/Funcionalidade:**  Recuperação de Senha
**Cenário de Teste:** Verificar o comportamento do sistema quando o usuário tenta recuperar senha informando e-mail não cadastrado.
**Pré-condições:** Estar na tela 'Esqueceu sua senha?'


### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Clicar na opção 'Esqueceu sua senha?'
4.  No campo 'E-mail' preecher com email não cadastrado.
5.  Clicar no botão 'Redefinir minha senha'.

### Dados de Teste:
* **E-mail:** `teste@email.com`

### Resultado Esperado:
* O sistema não deve enviar o link de recuperação de senha.
* O sistema deve mandar mensagem informando que o usuário precisa informar um e-mail cadastrado no sistema.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** FAILED
* **Observações:** O sistema enviou o link de recuperação mesmo com um e-mail não cadastrado e mostrou a mensagem 'Você recebeu um e-mail com o link para redefinir sua senha.'
