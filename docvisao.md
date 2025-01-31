# **Documento de Visão - Restaurant Menu SwiftUI Example App**

---

## **1. Introdução**

O *Restaurant Menu SwiftUI Example App* é um protótipo educacional que ilustra o desenvolvimento de um menu de restaurante utilizando SwiftUI. O objetivo é fornecer uma aplicação funcional e bem documentada que demonstre a criação de interfaces declarativas, organização de conteúdo por categorias e usabilidade. Este documento detalha os requisitos funcionais, não funcionais e as restrições do projeto, garantindo um desenvolvimento claro e direcionado. O sistema de menu digital do McDonald's foi utilizado como referência para a definição dos requisitos do projeto. Essa escolha foi baseada na sua interface intuitiva, experiência otimizada para usuários em restaurantes e organização eficiente dos itens do cardápio. Elementos como a separação dos produtos por categorias, a exibição de imagens de alta qualidade e a usabilidade responsiva foram considerados no escopo do sistema.

---

## **2. Objetivo do Projeto**

Criar um protótipo funcional para um menu de restaurante, destacando:  
- Organização dos itens por categorias.  
- Design intuitivo e responsivo.  
- Foco na experiência do usuário (UX/UI) em dispositivos iOS.  
- Código educacional que segue boas práticas de SwiftUI.

---

## **3. Escopo do Sistema**

O aplicativo permitirá:  
- Exibição de itens do menu organizados por categorias, como entradas, pratos principais, sobremesas e bebidas.  
- Visualização detalhada de cada item, incluindo nome, descrição, imagem e preço.  
- Navegação fluida e responsiva em diferentes dispositivos (iPhone e iPad).  
- Uma experiência educacional para desenvolvedores e designers interessados em SwiftUI.  

---

## **4. Requisitos Funcionais**

Os requisitos funcionais especificam as funcionalidades que o sistema deve oferecer.

- **RF01:** Permitir a visualização de itens do menu organizados em categorias.  
- **RF02:** Exibir detalhes de cada item, incluindo nome, descrição, preço e imagem.  
- **RF03:** Navegação fluida e responsiva entre as categorias do menu.  
- **RF04:** Permitir busca por itens do menu por nome ou categoria.  
- **RF05:** Adicionar um indicador visual para destacar os itens "mais populares".  
- **RF06:** Permitir o acesso ao menu de forma off-line, utilizando dados pré-carregados.  
- **RF07:** Exibir imagens dos pratos em alta resolução, otimizadas para diferentes tamanhos de tela.  
- **RF08:** Possibilitar a navegação de forma responsiva e adaptada a diferentes orientações (retrato e paisagem).  
- **RF09:** Implementar animações suaves para transições entre categorias e visualização de itens.  
- **RF10:** Fornecer um guia rápido dentro do aplicativo para orientar o usuário sobre como navegar no menu.

---

## **5. Requisitos Não Funcionais**

Os requisitos não funcionais determinam as características de qualidade do sistema.

- **RNF01:** A interface deve ser intuitiva, respeitando os princípios de design declarativo do SwiftUI.  
- **RNF02:** O sistema deve carregar os dados do menu em até 2 segundos.  
- **RNF03:** Garantir compatibilidade com dispositivos iOS 16 ou superior.  
- **RNF04:** O código deve ser modular, legível e seguir boas práticas de desenvolvimento em Swift.  
- **RNF05:** O design deve ser responsivo, garantindo consistência visual em dispositivos como iPhone SE (2ª geração) ou superior, iPads e monitores externos.  
- **RNF06:** O sistema deve consumir no máximo 50 MB de memória em execução.  
- **RNF07:** As animações de transição devem ser executadas em menos de 0,5 segundos.  
- **RNF08:** Deve-se garantir que o aplicativo funcione corretamente em modo off-line, com carregamento completo do menu.  
- **RNF09:** A aplicação deve exibir mensagens de erro claras em caso de falha no carregamento dos dados.  
- **RNF10:** O sistema deve ser otimizado para consumo mínimo de energia, permitindo uso prolongado em dispositivos móveis.  
- **RNF11:** Os testes de usabilidade devem garantir que 90% dos usuários consigam realizar as principais interações (ex.: navegação entre categorias) em menos de 10 segundos.  
- **RNF12:** O aplicativo deve ser responsivo em diferentes tamanhos de tela, com elementos ajustados automaticamente.

---

## **6. Restrições (Regras de Negócio)**

As restrições definem os limites dentro dos quais o sistema deve operar.

- **RN01:** O menu deve exibir apenas itens cadastrados e armazenados no código-fonte (não possui backend).  
- **RN02:** Não é permitido realizar alterações no menu diretamente pelo aplicativo (adicionar, editar ou excluir itens).  
- **RN03:** O protótipo deve ser desenvolvido exclusivamente em SwiftUI, sem o uso de UIKit ou frameworks externos.  
- **RN04:** O aplicativo será um exemplo educacional e não incluirá funcionalidades de pedido ou pagamento.  
- **RN05:** O sistema não deve utilizar bibliotecas externas, devendo depender apenas de recursos nativos do Swift e SwiftUI.  
- **RN06:** O layout e as funcionalidades devem seguir as diretrizes da Apple para aplicativos iOS.  
- **RN07:** O aplicativo não deve coletar ou armazenar dados pessoais dos usuários.  

---

## **7. Público-Alvo**

- Desenvolvedores iniciantes ou intermediários em Swift e SwiftUI que buscam entender a construção de interfaces declarativas.  
- Designers interessados em aplicar os princípios de UX/UI e responsividade em aplicativos para restaurantes.  
- Professores ou instrutores que desejam um exemplo didático para ensinar desenvolvimento em SwiftUI.  

---

## **8. Benefícios Esperados**

- Demonstrar o uso de SwiftUI para prototipagem de aplicativos responsivos.  
- Fornecer um exemplo prático, modular e educacional de desenvolvimento para iOS.  
- Facilitar o aprendizado de boas práticas de desenvolvimento Swift, organização de código e design centrado no usuário.  

---

## **9. Conclusão**

Este documento de visão detalha os requisitos e objetivos do *Restaurant Menu SwiftUI Example App*, servindo como guia para o desenvolvimento do protótipo. Com um foco educacional e exemplos práticos, o aplicativo visa demonstrar a capacidade do SwiftUI em criar interfaces modernas, eficientes e de alta usabilidade.

## **10. Correlação com ISO/IEC 25010**

| **Atributo da ISO/IEC 25010**      | **Descrição**                                                                                      | **Requisitos Relacionados**                                                                                  |
|------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| **Funcionalidade (Adequação Funcional)** | Capacidade de o sistema fornecer as funções que atendam às necessidades do usuário.               | **RF01**, **RF02**, **RF03**, **RF04**, **RF05**, **RF06**, **RF07**, **RF08**, **RF09**, **RF10**.         |
| **Desempenho e Eficiência**        | Capacidade do sistema de executar suas funções dentro de limites de tempo e recursos apropriados.  | **RNF02**, **RNF06**, **RNF07**, **RNF10**.                                                                 |
| **Usabilidade**                    | Facilidade com que o usuário pode aprender e operar o sistema.                                     | **RNF01**, **RNF05**, **RNF11**.                                                                            |
| **Confiabilidade**                 | Capacidade do sistema de manter o desempenho esperado em condições normais de operação.           | **RNF08**, **RNF09**, **RNF12**.                                                                            |
| **Manutenibilidade**               | Facilidade de modificar o sistema para corrigir defeitos ou melhorar funcionalidades.              | **RNF04**.                                                                                                  |
| **Portabilidade**                  | Capacidade do sistema de ser transferido para outros ambientes de execução.                       | **RNF03**, **RNF05**.   
