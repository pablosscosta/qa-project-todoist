## CT-LOG-003: Login com senha incorreta

**Módulo/Funcionalidade:**  Login de Usuário
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar realizar login com senha errada.
**Pré-condições:** Ter um e-mail válido de um usuário já cadastro no sistema.

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Na tela de login preencher o campo 'E-mail' com um e-mail válido de um usuário já cadastro e 'Senha' errada.
4.  Clicar no botão "Continuar" ou equivalente.  

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123`

### Resultado Esperado:
* O sistema não deve permitir o login.
* O sistema deve informar que os dados estão incorretos.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema não permitiu o login e mostrou a mensagem 'E-mail ou senha incorreto.'.
