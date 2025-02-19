# Atributos para Requisitos do Sistema

## Legenda dos Atributos:
- **Prioridade**: Indica a importância do requisito para o projeto. Pode ser: Alta, Média, Baixa.
- **Complexidade**: Refere-se à dificuldade de implementação do requisito. Pode ser: Alta, Média, Baixa.
- **Dependências**: Quais requisitos dependem deste para serem implementados.
- **Estado**: Indica o status atual do requisito. Pode ser: Implementado, Em Construção, Validado, Elicitado, Documentado.
- **Data de Implementação**: A data estimada ou real de implementação do requisito.
- **Responsável**: Quem é responsável pela implementação do requisito.

| Requisito | Descrição | Estado | Prioridade | Complexidade | Dependências | Data de Implementação | Responsável |
|-----------|-----------|--------|------------|--------------|--------------|-----------------------|-------------|
| **RF01** | Permitir a visualização de itens do menu organizados em categorias. | Implementado | Alta | Baixa | Nenhuma | 10/01/2025 | João |
| **RF02** | Exibir detalhes de cada item, incluindo nome, descrição, preço e imagem. | Implementado | Alta | Média | Nenhuma | 12/01/2025 | Maria |
| **RF03** | Navegação fluida e responsiva entre as categorias do menu. | Implementado | Alta | Média | RF01 | 15/01/2025 | João |
| **RF04** | Permitir busca por itens do menu por nome ou categoria. | Implementado | Alta | Alta | RF01 | 17/01/2025 | Carlos |
| **RF05** | Adicionar um indicador visual para destacar os itens "mais populares". | Validado | Média | Baixa | RF02 | 19/01/2025 | Maria |
| **RF06** | Permitir o acesso ao menu de forma off-line, utilizando dados pré-carregados. | Em Mudança | Alta | Alta | Nenhuma | 22/01/2025 | Lucas |
| **RF07** | Exibir imagens dos pratos em alta resolução, otimizadas para diferentes tamanhos de tela. | Implementado | Alta | Média | RF02 | 25/01/2025 | Pedro |
| **RF08** | Possibilitar a navegação de forma responsiva e adaptada a diferentes orientações (retrato e paisagem). | Em Construção | Alta | Alta | RF03 | 28/01/2025 | João |
| **RF09** | Implementar animações suaves para transições entre categorias e visualização de itens. | Documentado | Média | Alta | RF03 | 30/01/2025 | Maria |
| **RF10** | Fornecer um guia rápido dentro do aplicativo para orientar o usuário sobre como navegar no menu. | Elicitado | Baixa | Baixa | Nenhuma | 02/02/2025 | Carlos |
| **RNF01** | A interface deve ser intuitiva, respeitando os princípios de design declarativo do SwiftUI. | Implementado | Alta | Baixa | Nenhuma | 05/02/2025 | João |
| **RNF02** | O sistema deve carregar os dados do menu em até 2 segundos. | Validado | Alta | Alta | RF06 | 07/02/2025 | Pedro |
| **RNF03** | Garantir compatibilidade com dispositivos iOS 16 ou superior. | Implementado | Alta | Baixa | Nenhuma | 09/02/2025 | Carlos |
| **RNF04** | O código deve ser modular, legível e seguir boas práticas de desenvolvimento em Swift. | Em Construção | Alta | Alta | Nenhuma | 11/02/2025 | Lucas |
| **RNF05** | O design deve ser responsivo, garantindo consistência visual em dispositivos como iPhone SE (2ª geração) ou superior, iPads e monitores externos. | Em Mudança | Alta | Alta | RF01 | 13/02/2025 | Maria |
| **RNF06** | O sistema deve consumir no máximo 50 MB de memória em execução. | Validado | Alta | Média | Nenhuma | 15/02/2025 | João |
| **RNF07** | As animações de transição devem ser executadas em menos de 0,5 segundos. | Documentado | Média | Alta | RF09 | 17/02/2025 | Carlos |
| **RNF08** | Deve-se garantir que o aplicativo funcione corretamente em modo off-line, com carregamento completo do menu. | Em Construção | Alta | Alta | RF06 | 20/02/2025 | Lucas |
| **RNF09** | A aplicação deve exibir mensagens de erro claras em caso de falha no carregamento dos dados. | Implementado | Alta | Baixa | RF06 | 23/02/2025 | Pedro |
| **RNF10** | O sistema deve ser otimizado para consumo mínimo de energia, permitindo uso prolongado em dispositivos móveis. | Validado | Média | Baixa | Nenhuma | 25/02/2025 | João |
| **RNF11** | Os testes de usabilidade devem garantir que 90% dos usuários consigam realizar as principais interações (ex.: navegação entre categorias) em menos de 10 segundos. | Documentado | Alta | Média | RF03 | 27/02/2025 | Maria |
| **RNF12** | O aplicativo deve ser responsivo em diferentes tamanhos de tela, com elementos ajustados automaticamente. | Em Construção | Alta | Alta | RF01 | 02/03/2025 | Lucas |
