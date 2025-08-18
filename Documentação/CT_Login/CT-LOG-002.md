## CT-LOG-002: Tentativa de Login com E-mail em branco e Senha preenchida

**Módulo/Funcionalidade:**  Login de Usuário
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar realizar login com o campo de 'E-mail' em branco e 'Senha' preenchido
**Pré-condições:** Não há pré-condições para esse cenário

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Na tela de login não preencher o campo 'E-mail' e preencher o compo 'Senha' com no mínimo 8 caracteres
4.  Clicar no botão "Continuar" ou equivalente. 

### Dados de Teste:
* **E-mail:** Em branco
* **Senha:** SenhaForte123!

### Resultado Esperado:
* O sistema não deve permitir o login
* O sistema deve mostrar uma mensagem clara informando que o e-mail deve ser preenchidos com informações cadastradas anteriormente.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema não permitiu o login. E apresentou a mensagem 'Insira um endereço de e-mail válido.' logo acima do campo 'E-mail' 
