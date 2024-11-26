| **Nome**                             | Visualizar o Menu                                                                                   |
|--------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Pré-condição**                     | O aplicativo deve estar instalado e em execução. Os dados do menu devem estar previamente cadastrados no código. |
| **Pós-condição em caso de sucesso**  | O usuário visualiza as categorias e itens do menu com detalhes (nome, descrição e preço).          |
| **Pós-condição em caso de falha**    | Uma mensagem de erro é exibida, indicando que os dados do menu não podem ser carregados.           |
| **Ator principal**                   | Usuário (cliente do restaurante).                                                                  |
| **Outros atores**                    | Nenhum.                                                                                            |
| **Evento disparador**                | O usuário abre o aplicativo e acessa a tela inicial.                                               |
| **Fluxo Normal**                     | 1. O usuário abre o aplicativo.                                                                    |
|                                      | 2. O sistema carrega os dados do menu.                                                             |
|                                      | 3. O sistema exibe as categorias disponíveis (ex.: entradas, pratos principais, sobremesas).       |
|                                      | 4. O usuário seleciona uma categoria.                                                              |
|                                      | 5. O sistema exibe a lista de itens da categoria selecionada, incluindo o nome, descrição e preço de cada item. |
| **Fluxos Alternativos e de Exceção** | **FA01:**                                                                                          |
|                                      | **Condição:** Falha ao carregar os dados do menu.                                                  |
|                                      | **Ação:** O sistema exibe uma mensagem de erro: *"Não foi possível carregar os dados do menu. Tente novamente mais tarde."* |
| **Extensões**                        | Possível caso de uso futuro: Implementação de um sistema de busca para localizar itens do menu por palavras-chave. |
| **Informações Relacionadas**         | - Este caso de uso é central no protótipo, sendo a principal funcionalidade do aplicativo.          |
|                                      | - Frequência esperada de uso: alta, sempre que o aplicativo for acessado.                          |
|                                      | - Relacionado a melhorias futuras, como busca por itens e integração com funcionalidades de pedidos. |
