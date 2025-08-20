## CT-US-001: Responsividade da Dashboard (Dispositivos Móveis)

**Módulo/Funcionalidade:** Usabilidade / Responsividade
**Cenário de Teste:** Verificar se a interface da dashboard se adapta corretamente a telas de dispositivos móveis.
**Pré-condições:** Estar logado na plataforma. Ter acesso às ferramentas de desenvolvedor do navegador.

### Passos de Execução:
1.  Acessar a URL `https://www.todoist.com/pt-BR` após o login.
2.  Abrir as ferramentas de desenvolvedor do navegador (geralmente com F12 ou `Ctrl+Shift+I`).
3.  Ativar o modo de visualização de dispositivos móveis (o ícone de um celular e um tablet).
4.  Selecionar a dimensão de tela de um dispositivo comum, como um "iPhone SE" ou um "Galaxy S8".
5.  Observar o comportamento visual da interface.

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`
* **Elementos a Observar:** Barra lateral, lista de tarefas, botões de adicionar tarefa, ícones, fontes.

### Resultado Esperado:
* A barra lateral esquerda deve ser recolhida ou escondida.
* As tarefas e botões devem se reorganizar para se ajustarem à largura menor da tela.
* A barra lateral deve ser acessível através de um ícone de menu hambúrguer ou similar.
* Não deve haver barras de rolagem horizontais.

### Status de Execução:
* **Data da Execução:** 20/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema se comportou como esperado. A barra lateral se escondeu e a interface se adaptou corretamente ao tamanho do celular.
