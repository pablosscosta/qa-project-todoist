## CT-CAD-006: Validação do Segundo Formulário de Cadastro e Campo Nome de Usuário

**Módulo/Funcionalidade:** Cadastro de Usuário (Segundo Formulário)  
**Cenário de Teste:** Verificar a validação do campo 'Seu nome' e o preenchimento bem-sucedido no segundo formulário de cadastro.  
**Pré-condições:** Usuário deve ter preenchido o primeiro formulário de cadastro (E-mail e Senha) com dados válidos e estar aguardando a finalização do cadastro.

### Passos de Execução:
1.  **Cenário 1: Campo 'Seu nome' Vazio**
    1.1. Assegurar que o usuário está na tela do segundo formulário de cadastro (após preencher e-mail e senha no primeiro formulário).
    1.2. Deixar o campo 'Carregar foto' em branco (opcional).
    1.3. Deixar o campo 'Seu nome' em **branco**.
    1.4. Deixar a opção 'Quero usar o Todoist com a minha equipe' em seu estado padrão.
    1.5. Clicar no botão "Continuar".
    1.6. Observar a resposta do sistema.

2.  **Cenário 2: Preenchimento Válido do Campo 'Seu nome'**
    2.1. Assegurar que o usuário está na tela do segundo formulário de cadastro (após preencher e-mail e senha no primeiro formulário). **Para este passo, é necessário iniciar um novo fluxo de cadastro para ter um e-mail válido disponível.**
    2.2. Deixar o campo 'Carregar foto' em branco (opcional).
    2.3. Preencher o campo 'Seu nome' com um nome válido (Ex: 'Pablo Tester QA').
    2.4. Deixar a opção 'Quero usar o Todoist com a minha equipe' em seu estado padrão (aparentemente opcional).
    2.5. Clicar no botão "Continuar".
    2.6. Na tela "Como você pretende usar o Todoist?", selecionar a opção "Pessoal".
    2.7. Clicar no botão "Continuar".
    2.8. Verificar redirecionamento para a dashboard e pop-up de verificação de e-mail.
    2.9. Acessar o e-mail cadastrado (via temp-mail.org) e clicar no link de verificação.
    2.10. Verificar que o pop-up de confirmação desaparece e a dashboard está funcional.

### Dados de Teste:
* **E-mail (para pré-condição do Cenário 1):** `foyix31279@devdigs.com`
* **Senha (para pré-condição do Cenário 1):** `SenhaDeTeste123!`
* **E-mail (para pré-condição do Cenário 2):** `foyix31279@devdigs.com`
* **Senha (para pré-condição do Cenário 2):** `SenhaDeTeste123!`
* **Nome para Cenário 1:** `[Deixar em branco]`
* **Nome para Cenário 2:** `Pablo Tester QA`

### Resultado Esperado:
* **Cenário 1:**
    * O sistema deve impedir o avanço para a próxima tela.
    * O sistema deve exibir uma mensagem de erro clara indicando que o campo 'Seu nome' é obrigatório.
* **Cenário 2:**
    * O sistema deve permitir o avanço para a próxima tela ("Como você pretende usar o Todoist?").
    * Após seleção da opção de uso, o usuário deve ser redirecionado para a dashboard.
    * Pop-up de verificação de e-mail deve aparecer.
    * E-mail de verificação deve ser enviado e, após clique no link, a conta deve ser verificada com sucesso.

### Status de Execução:
* **Data da Execução:** 30/07/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:**
    * **Cenário 1 (Campo 'Seu nome' Vazio):** O botão "Continuar" permaneceu indisponível (ou "inclicável"), impedindo o avanço do cadastro.
    * **Cenário 2 (Preenchimento Válido):** O sistema avançou para o próximo formulário ("Como você pretende usar o Todoist?") conforme esperado.
