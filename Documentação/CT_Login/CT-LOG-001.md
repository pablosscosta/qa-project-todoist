## CT-LOG-001: Tentativa de Login com E-mail e Senha em branco

**Módulo/Funcionalidade:**  Login de Usuário
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar realizar login com os campos de 'E-mail' e 'Senha'
**Pré-condições:** Não há pré-condições para esse cenário

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Na tela de login não preencher os campos 'E-mail' e 'Senha'
4.  Clicar no botão "Continuar" ou equivalente. 

### Dados de Teste:
* **E-mail:** Em branco
* **Senha:** Em branco

### Resultado Esperado:
* O sistema não deve permitir o login
* O sistema deve mostrar uma mensagem clara informando que o e-mail e senha devem ser preenchidos com informações cadastradas anteriormente.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema não permitiu o login e apresentou a mensagem abaixo do campo de senha 'A senha deve conter no mínimo 8 caracteres'. Para uma melhor instrução também deveria ter uma mensagem referente ao campo de e-mail.
