## CT-REC-004: Tentar redefinir senha em branco

**Módulo/Funcionalidade:**  Recuperação de Senha
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar redefinição de senha em branco.
**Pré-condições:** Estar na tela 'Esqueceu sua senha?'

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'
3.  Clicar na opção 'Esqueceu sua senha?'
4.  Fornecedor e-mail com formato válido e cadastrado no sistema.
5.  Clicar no botão "Redefinir minha senha".
6.  Acessar a caixa de entrada do email informado e clicar no link.
7.  Na tela 'Redefinir Senha' tentar avançar com os campos em branco.

### Dados de Teste:
* **E-mail:** giwegib752@futebr.com

### Resultado Esperado:
* O sistema deve enviar o link de recuperação para o email.
* Na tela de 'Redefinir Senha' o sistema deve mostrar alguma mensagem para informar ao usuário que ele deve preencher a senha.

### Status de Execução:
* **Data da Execução:** 18/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** Ao tentar redefinir uma senha em branco o sistema informou a mensagem 'A senha deve conter no mínimo 8 caracteres'
