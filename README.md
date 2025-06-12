# 🔺 UaiCine - Plataforma de Streaming de Filmes

UaiCine é um projeto de front-end que simula uma plataforma de streaming de filmes e séries, com uma interface moderna e interativa. O projeto utiliza tecnologias web essenciais para criar uma experiência de usuário rica, incluindo cadastro, login, exploração de conteúdo e uma lista de favoritos, com dados de filmes e séries consumidos diretamente da API do The Movie Database (TMDb).

---

## ✨ Funcionalidades

O projeto é dividido em várias páginas, cada uma com funcionalidades específicas:

-   **Página de Cadastro (`Validação.html`)**
    * Formulário completo para registro de novos usuários com campos para nome, curso, e-mail, senha e redes sociais.
    * Validação de preenchimento dos campos obrigatórios via JavaScript.
    * Armazena os dados do usuário no `localStorage` do navegador para simular a criação de uma conta.

-   **Página de Login (`Cadastro.html`)**
    * Interface de login que verifica as credenciais do usuário com os dados salvos no `localStorage`.
    * Redireciona para a página principal (`index.html`) em caso de sucesso no login.
    * Interface estilizada com Tailwind CSS e animações personalizadas em CSS.

-   **Página Principal (`index.html`)**
    * Apresenta um carrossel principal com filmes em destaque.
    * Exibe seções de filmes "Recomendados" e "Adicionados Recentemente", consumindo dados da API do TMDb.
    * Possui uma barra de pesquisa para encontrar filmes e séries.

-   **Página de Exploração (`explore.html`)**
    * Permite ao usuário pesquisar e descobrir novos filmes e séries.
    * O conteúdo é filtrado dinamicamente conforme o usuário digita na barra de pesquisa.

-   **Página de Favoritos (`favoritos.html`)**
    * Exibe uma galeria personalizada com os filmes que o usuário marcou como favoritos.
    * Os filmes são carregados dinamicamente a partir de uma lista de IDs salva no `localStorage`.
    * Permite remover filmes da lista de favoritos.

---

## 🚀 Tecnologias e Recursos

* **Front-end:** HTML5, CSS3, JavaScript
* **Frameworks CSS:**
    * **Tailwind CSS:** Utilizado para a estilização rápida das páginas de login e cadastro.
    * **Bootstrap:** Usado para o layout responsivo e componentes nas páginas principal, de exploração e de favoritos.
* **API Externa:** **The Movie Database (TMDb)** para buscar e exibir dados de filmes e séries de forma dinâmica.
* **Armazenamento no Navegador:** **`localStorage`** é utilizado para persistir os dados de cadastro do usuário e a lista de filmes favoritos.

---

## 📂 Estrutura do Projeto

/
├── Cadastro.html       # Página de login do usuário.
├── explore.html        # Página para pesquisar e explorar o catálogo.
├── favoritos.html      # Página para exibir os filmes favoritados.
├── index.html          # Página principal da aplicação (Home).
├── Validação.html      # Página de cadastro de novos usuários.
└── Imagem [...].jpg    # Logo do projeto.

---

## 🏁 Como Executar

Por ser um projeto de front-end que utiliza o `localStorage`, não é necessário um servidor. Você pode executá-lo diretamente no navegador:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/uai-cine.git](https://github.com/seu-usuario/uai-cine.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd uai-cine
    ```
3.  **Abra o arquivo `Validação.html`** no seu navegador para se cadastrar. Em seguida, utilize o `Cadastro.html` para fazer o login e acessar o site.

---

## 🔮 Melhorias Futuras

-   [ ] Implementar um back-end real com banco de dados para gerenciar usuários e favoritos.
-   [ ] Adicionar paginação na exibição de filmes e resultados de busca.
-   [ ] Criar uma página de detalhes para cada filme/série ao invés de redirecionar para o TMDb.
-   [ ] Refatorar o código JavaScript para uma estrutura mais modular ou utilizar um framework como React ou Vue.js.
-   [ ] Aprimorar a acessibilidade e a performance geral do site.
