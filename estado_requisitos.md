# **4. Requisitos Funcionais**

Os requisitos funcionais especificam as funcionalidades que o sistema deve oferecer.

| ID   | Descrição | Estado |
|------|-----------|--------|
| **RF01** | Permitir a visualização de itens do menu organizados em categorias. | Implementado |
| **RF02** | Exibir detalhes de cada item, incluindo nome, descrição, preço e imagem. | Implementado |
| **RF03** | Navegação fluida e responsiva entre as categorias do menu. | Implementado |
| **RF04** | Permitir busca por itens do menu por nome ou categoria. | Implementado |
| **RF05** | Adicionar um indicador visual para destacar os itens "mais populares". | Validado |
| **RF06** | Permitir o acesso ao menu de forma off-line, utilizando dados pré-carregados. | Em Mudança |
| **RF07** | Exibir imagens dos pratos em alta resolução, otimizadas para diferentes tamanhos de tela. | Implementado |
| **RF08** | Possibilitar a navegação de forma responsiva e adaptada a diferentes orientações (retrato e paisagem). | Em Construção |
| **RF09** | Implementar animações suaves para transições entre categorias e visualização de itens. | Documentado |
| **RF10** | Fornecer um guia rápido dentro do aplicativo para orientar o usuário sobre como navegar no menu. | Elicitado |

---

# **5. Requisitos Não Funcionais**

Os requisitos não funcionais determinam as características de qualidade do sistema.

| ID   | Descrição | Estado |
|------|-----------|--------|
| **RNF01** | A interface deve ser intuitiva, respeitando os princípios de design declarativo do SwiftUI. | Implementado |
| **RNF02** | O sistema deve carregar os dados do menu em até 2 segundos. | Validado |
| **RNF03** | Garantir compatibilidade com dispositivos iOS 16 ou superior. | Implementado |
| **RNF04** | O código deve ser modular, legível e seguir boas práticas de desenvolvimento em Swift. | Em Construção |
| **RNF05** | O design deve ser responsivo, garantindo consistência visual em dispositivos como iPhone SE (2ª geração) ou superior, iPads e monitores externos. | Em Mudança |
| **RNF06** | O sistema deve consumir no máximo 50 MB de memória em execução. | Validado |
| **RNF07** | As animações de transição devem ser executadas em menos de 0,5 segundos. | Documentado |
| **RNF08** | Deve-se garantir que o aplicativo funcione corretamente em modo off-line, com carregamento completo do menu. | Em Construção |
| **RNF09** | A aplicação deve exibir mensagens de erro claras em caso de falha no carregamento dos dados. | Implementado |
| **RNF10** | O sistema deve ser otimizado para consumo mínimo de energia, permitindo uso prolongado em dispositivos móveis. | Validado |
| **RNF11** | Os testes de usabilidade devem garantir que 90% dos usuários consigam realizar as principais interações (ex.: navegação entre categorias) em menos de 10 segundos. | Documentado |
| **RNF12** | O aplicativo deve ser responsivo em diferentes tamanhos de tela, com elementos ajustados automaticamente. | Em Construção |

