## CT-CAD-002: Tentativa de cadastro com e-mail já cadastrado anteriormente na plataforma.

**Módulo/Funcionalidade:** Cadastro de Usuário  
**Cenário de Teste:** Verificar o cadastro de um novo usuário utilizando um e-mail já cadastrado na plataforma.  
**Pré-condições:** Ter um conta já cadastrada no sistema.  

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão "Comece de graça".
3.  No formulário de cadastro, preencher o campo 'E-mail' com um e-mail cadastrado anteriormente (Ex: `litagob991@coursora.com`).
4.  Preencher o campo 'Senha' com uma senha válida (Ex: `SenhaDeTeste123!`).
5.  Clicar no botão "Continuar" ou equivalente.

### Dados de Teste:
* **E-mail:** `litagob991@coursora.com` (ou um e-mail gerado por um serviço temporário)
* **Senha:** `SenhaDeTeste123!` (Uma senha forte, mas que **não é uma senha real** sua)

### Resultado Esperado:
* O sistema deve exibir a mensagem de erro: "Ah, não, este endereço de e-mail está indisponível! Tente com outro."
* O usuário deve permanecer na mesma página de cadastro, sem ser redirecionado para a próxima etapa ou para a dashboard.

### Status de Execução:
* **Data da Execução:** 29/07/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** Sistema não permitiu cadastro com e-mail cadastrado anteriormente e mostro uma mensagem de erro.
