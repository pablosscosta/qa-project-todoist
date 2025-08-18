## BUG-CT-REC-003: O sistema envia link de recuperação de senha para e-mails não cadastrados

**Módulo/Funcionalidade:** Recuperação de Senha

**Prioridade:** Alta (Falha de Segurança)

**Ambiente:** Google Chrome Versão 139.0.7258.127 (Versão oficial) 64 bits / Linux Mint 22 Cinnamon Versão 6.2.9

### Passos para Reproduzir:
1.  Acessar a URL: `https://www.todoist.com/pt-BR`
2.  Clicar no botão 'Login'.
3.  Clicar na opção 'Esqueceu sua senha?'.
4.  No campo 'E-mail', preencher com um e-mail não cadastrado (ex: `teste@email.com`).
5.  Clicar no botão "Redefinir minha senha".

### Resultado Esperado:
* O sistema não deve enviar o link de recuperação de senha.
* O sistema deve exibir uma mensagem informando que não foi possível encontrar o e-mail (ou uma mensagem genérica, mas segura).

### Resultado Real:
* O sistema exibiu a mensagem 'Você recebeu um e-mail com o link para redefinir sua senha.', o que confirma a existência do e-mail na plataforma mesmo quando ele não está cadastrado.
