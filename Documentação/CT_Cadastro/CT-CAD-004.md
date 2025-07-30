## CT-CAD-004: Tentativa de cadastro com os campos submetidos com nenhum valor

**Módulo/Funcionalidade:** Cadastro de Usuário  
**Cenário de Teste:** Verificar a resposta do sistema quando o usuário tenta cadastro sem preencher os campos. 
**Pré-condições:** Não há pré-condições.  

### Passos de Execução:
1.  Acessar a URL: https://www.todoist.com/pt-BR
2.  Clicar no botão "Comece de graça".
3.  No formulário de cadastro, não preencher os campos 'E-mail' e 'Senha'
4.  Clicar no botão "Continuar" ou equivalente.

### Dados de Teste:
* **E-mail:** Em branco
* **Senha:** Em branco

### Resultado Esperado:
* O sistema deve impedir o avanço do cadastro.
* O sistema deve exibir mensagem informando ao usuário que deve preencher os campos.

### Status de Execução:
* **Data da Execução:** 30/07/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema exibiu a mensagem: "Insira um endereço de e-mail válido."
