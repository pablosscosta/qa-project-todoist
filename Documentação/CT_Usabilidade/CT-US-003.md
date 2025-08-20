## CT-US-003: Acessibilidade de Cores e Contraste

**Módulo/Funcionalidade:** Usabilidade / Acessibilidade
**Cenário de Teste:** Verificar se o contraste de cores da interface do usuário é suficiente para garantir a legibilidade.
**Pré-condições:**
* Estar logado na plataforma.
* Ter uma extensão de navegador para análise de contraste (ex: Color Contrast Analyzer, WCAG Color Contrast Checker).

### Passos de Execução:
1.  Acessar a dashboard após o login.
2.  Abrir a ferramenta de análise de contraste.
3.  Analisar o contraste entre a cor da fonte e a cor do fundo de diferentes elementos da página.
4.  Checar os botões e outros elementos interativos para garantir que são distinguíveis do fundo.

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`
* **Elementos a Observar:** Títulos das tarefas, texto da descrição, botões da barra lateral, ícones.

### Resultado Esperado:
* As combinações de cores devem ter um contraste mínimo de 4.5:1 para texto normal, de acordo com o padrão **WCAG 2.1 AA**.
* Todas as fontes devem ser facilmente legíveis.

### Status de Execução:
* **Data da Execução:** 20/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** Todas as combinações de cores testadas na dashboard, incluindo texto e ícones, atenderam aos requisitos de contraste mínimo, garantindo uma boa legibilidade.
