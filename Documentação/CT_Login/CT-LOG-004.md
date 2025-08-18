## CT-LOG-004: Tentativa de Login com E-mail Não Cadastrado

**Módulo/Funcionalidade:**  Login de Usuário
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar realizar o login com um e-mail não cadastrado.
**Pré-condições:** Não há pré-condições.

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Na tela de login preencher o campo 'E-mail' com uma e-mail não cadastrado no sistema e 'Senha' com uma senha qualquer.
4.   Clicar no botão "Continuar" ou equivalente.

### Dados de Teste:
* **E-mail:** `teste@email.com`
* **Senha:**  `SenhaDeTeste123!`

### Resultado Esperado:
* O sistema não deve permitir o login.
* O sistema deve mostrar alguma mensagem informado que não é possível realizar login com o e-mail informado.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema não permitiu o login e mostrou a mensagem 'E-mail ou senha incorreto.'.
