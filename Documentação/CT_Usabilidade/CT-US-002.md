## CT-US-002: Navegação por Teclado na Dashboard

**Módulo/Funcionalidade:** Usabilidade / Acessibilidade
**Cenário de Teste:** Verificar se a navegação e interação com a dashboard são possíveis usando apenas o teclado.
**Pré-condições:** Estar logado na plataforma.

### Passos de Execução:
1.  Acessar a dashboard após login.
2.  Pressionar a tecla **`Tab`** repetidamente para navegar pelos elementos da interface (links, botões, campos de texto, etc.).
3.  Pressionar **`Shift + Tab`** para navegar em ordem reversa.
4.  Pressionar **`Enter`** ou **`Espaço`** para acionar um elemento em foco.

### Dados de Teste:
* **E-mail:** `giwegib752@futebr.com`
* **Senha:** `SenhaForte123!`
* **Elementos a Observar:** Barra lateral, botão de adicionar tarefa, botões de edição/exclusão, campo de busca.

### Resultado Esperado:
* A navegação deve seguir uma ordem lógica e intuitiva.
* O elemento focado deve ser destacado com um contorno visível (indicador de foco).
* Todos os elementos interativos devem ser acessíveis e acionáveis pelo teclado.

### Status de Execução:
* **Data da Execução:** 20/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** Foi possível navegar por todos os elementos interativos da página usando apenas as teclas `Tab` e `Shift + Tab`. O indicador de foco se mostrou visível em todos os elementos.
