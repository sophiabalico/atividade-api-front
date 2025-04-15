# Documentação do Projeto - Lista de Personagens

Este documento descreve todas as etapas e funcionalidades implementadas no projeto de consumo de API para exibição de uma lista de personagens.

---

## Descrição do Projeto

O projeto foi desenvolvido utilizando **Next.js** e tem como objetivo consumir uma API externa para exibir uma lista de personagens com informações detalhadas. Ele inclui funcionalidades como carregamento dinâmico, tratamento de erros e layout responsivo.

---

## Funcionalidades Implementadas

1. **Consumo de API Externa**:
   - Integração com uma API para buscar dados de personagens.
   - Exibição de informações como nome, data de nascimento, espécie, casa e pontuação.

2. **Interface Responsiva**:
   - Layout adaptado para diferentes tamanhos de tela utilizando CSS e media queries.

3. **Componentização**:
   - Criação de componentes reutilizáveis para organizar o código e facilitar a manutenção.

4. **Feedback Visual**:
   - Mensagens de carregamento enquanto os dados são buscados.
   - Exibição de mensagens de erro em caso de falha na requisição.

5. **Estilização com CSS Modules**:
   - Estilos encapsulados para evitar conflitos e garantir modularidade.

6. **Efeitos Visuais**:
   - Animações e transições para melhorar a experiência do usuário, como hover nos cartões de personagens.

---

---

## Tecnologias Utilizadas

- **Next.js**: Framework React para renderização do lado do servidor e geração de páginas estáticas.
- **CSS Modules**: Para estilização modular e escopo local.
- **Fetch API/Axios**: Para realizar requisições à API externa.
- **HTML5 e CSS3**: Para estruturação e estilização da interface.

---

## Estilização (CSS)

O arquivo `characterList.module.css` foi utilizado para estilizar o componente principal. Ele inclui:

- Layout centralizado e responsivo.
- Estilização de cartões com efeitos de hover.
- Feedback visual para estados de carregamento e erro.
- Media queries para adaptação em dispositivos móveis.

---

## Passos Realizados no Desenvolvimento

1. **Configuração Inicial**:
   - Criação do projeto Next.js.
   - Configuração do ambiente de desenvolvimento.

2. **Criação do Componente Principal**:
   - Desenvolvimento do componente `CharacterList` para exibir os personagens.
   - Implementação da lógica para consumir a API e renderizar os dados.

3. **Estilização**:
   - Criação do arquivo `characterList.module.css` para estilizar o componente.
   - Implementação de responsividade e efeitos visuais.

4. **Tratamento de Estados**:
   - Adição de mensagens de carregamento e erro para melhorar a experiência do usuário.

5. **Testes Locais**:
   - Testes no ambiente de desenvolvimento para garantir o funcionamento correto.

---

## Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>

2. Instale as dependências:
```npm install

3. Inicie o servidor de desenvolvimento:

```npm run dev

4. Abra o navegador e acesse http://localhost:3000.