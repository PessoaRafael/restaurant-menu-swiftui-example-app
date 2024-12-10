# **Caso de Uso: Visualizar o Menu**

---

## **Descrição**
Este caso de uso permite que o usuário visualize as categorias e itens disponíveis no menu do restaurante, com detalhes como nome, descrição e preço. Ele representa a funcionalidade central do *Restaurant Menu SwiftUI Example App*.

---

## **Detalhes do Caso de Uso**

| **Nome**                             | Visualizar o Menu                                                                                   |
|--------------------------------------|-----------------------------------------------------------------------------------------------------|
| **ID**                               | CDU01                                                                                              |
| **Objetivo Primário**                | Permitir ao usuário acessar e visualizar as categorias e itens do menu de forma intuitiva.         |
| **Pré-condição**                     | - O aplicativo deve estar instalado e em execução.                                                 |
|                                      | - Os dados do menu devem estar cadastrados previamente no código-fonte.                            |
| **Pós-condição em caso de sucesso**  | - O usuário visualiza as categorias disponíveis no menu.                                            |
|                                      | - O usuário visualiza a lista de itens dentro de cada categoria, incluindo detalhes como nome, descrição e preço. |
| **Pós-condição em caso de falha**    | - O sistema exibe uma mensagem de erro informando a impossibilidade de carregar os dados do menu.  |
| **Ator Principal**                   | Usuário (cliente do restaurante).                                                                  |
| **Outros Atores**                    | Nenhum.                                                                                            |
| **Evento Disparador**                | O usuário abre o aplicativo e acessa a tela inicial.                                               |

---

## **Fluxo Principal (Normal)**

1. O usuário abre o aplicativo.  
2. O sistema verifica se os dados do menu estão disponíveis e inicia o carregamento.  
3. O sistema exibe a tela inicial, apresentando as categorias disponíveis (ex.: entradas, pratos principais, sobremesas).  
4. O usuário seleciona uma categoria.  
5. O sistema exibe uma lista de itens pertencentes à categoria selecionada, incluindo:  
   - Nome do item.  
   - Descrição do item.  
   - Preço do item.  
   - Imagem do item (se disponível).  
6. O usuário pode retornar à lista de categorias ou navegar para outras categorias.  

---

## **Fluxos Alternativos e de Exceção**

### **FA01 - Falha ao carregar os dados do menu**  
- **Condição:**  
  O sistema não consegue carregar os dados do menu.  
- **Ação:**  
  O sistema exibe a mensagem de erro:  
  _"Não foi possível carregar os dados do menu. Tente novamente mais tarde."_  
- **Extensão:**  
  O sistema pode oferecer uma opção para tentar recarregar os dados.

### **FA02 - Navegação para uma categoria vazia**  
- **Condição:**  
  O usuário seleciona uma categoria que não possui itens cadastrados.  
- **Ação:**  
  O sistema exibe uma mensagem informativa:  
  _"Nenhum item disponível nesta categoria."_  
- **Extensão:**  
  O sistema retorna à tela de categorias ou permite navegar para outras categorias.  

---

## **Fluxo de Exceção Global**

1. **Erro inesperado:**  
   - **Condição:** Qualquer erro não mapeado ocorre durante a execução do aplicativo.  
   - **Ação:** O sistema exibe uma mensagem genérica de erro:  
     _"Ocorreu um erro inesperado. Reinicie o aplicativo."_  

---

## **Extensões e Melhorias Futuras**

- **Sistema de Busca:**  
  Permitir que o usuário busque itens do menu por palavras-chave.  
- **Destaques:**  
  Implementar indicadores visuais para itens populares ou em promoção.  
- **Modo Noturno:**  
  Adicionar um tema escuro para melhorar a experiência do usuário em ambientes com pouca luz.  

---

## **Informações Relacionadas**

- **Frequência esperada de uso:** Alta, pois este é o caso de uso principal do aplicativo.  
- **Requisitos Funcionais Relacionados:**  
  - **RF01:** Permitir a visualização de itens do menu.  
  - **RF02:** Organizar os itens do menu por categorias.  
  - **RF03:** Exibir detalhes de cada item, como nome, descrição e preço.  
  - **RF08:** Garantir que o sistema funcione off-line, carregando dados pré-configurados.  
- **Requisitos Não Funcionais Relacionados:**  
  - **RNF02:** Carregar os dados do menu em até 2 segundos.  
  - **RNF07:** As animações de transição devem ser executadas em menos de 0,5 segundos.  
  - **RNF09:** Exibir mensagens de erro claras e informativas.  
