# Casos de Teste - Módulo de Cadastro

---

## CT-CAD-001: Cadastro de Novo Usuário com E-mail e Senha Válidos

**Módulo/Funcionalidade:** Cadastro de Usuário  
**Cenário de Teste:** Verificar o cadastro bem-sucedido de um novo usuário com dados válidos.  
**Pré-condições:** Nenhuma conta existente com o e-mail de teste.  

### Passos de Execução:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão "Comece de graça".
3.  No formulário de cadastro, preencher o campo 'E-mail' com um e-mail válido, não cadastrado anteriormente e que tenha acesso pois será necessário validar via link que será enviado ao e-mail informado (Ex: `litagob991@coursora.com`).
4.  Preencher o campo 'Senha' com uma senha válida (Ex: `SenhaDeTeste123!`).
5.  Clicar no botão "Continuar" ou equivalente.
6.  Preencher o campo 'Nome de usuário' (Ex: `UsuarioTesteQA`).
7.  Clicar em "Continuar" ou equivalente (se houver a opção "Quero usar o Todoist com minha equipe", ignorar ou deixar padrão).
8.  Selecionar pelo menos uma opção em "Como você pretende usar o Todoist?" (Ex: "Pessoal").
9.  Clicar no botão "Continuar".
10. Verificar a aparição da pop-up de confirmação de e-mail.
11. Acessar o e-mail cadastrado e clicar no link de verificação.
12. Verificar que o pop-up de confirmação de e-mail desaparece e que a dashboard está totalmente funcional.

### Dados de Teste:
* **E-mail:** `litagob991@coursora.com` (ou um e-mail gerado por um serviço temporário)
* **Senha:** `SenhaDeTeste123!` (Uma senha forte, mas que **não é uma senha real** sua)
* **Nome de Usuário:** `UsuarioTesteQA`
* **Uso:** `Pessoal`

### Resultado Esperado:
* O sistema deve permitir o cadastro.
* O usuário deve ser redirecionado para a dashboard do Todoist.
* Uma pop-up informando sobre a verificação de e-mail deve aparecer.
* Um e-mail de verificação deve ser enviado para o endereço fornecido.
* Após a verificação do e-mail, o pop-up deve desaparecer e o usuário deve ter acesso completo à dashboard.

### Status de Execução:
* **Data da Execução:** 28/07/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** Cadastro concluído e e-mail verificado com sucesso.
