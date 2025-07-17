# Assistente de Meta para Games com IA Gemini

Bem-vindo ao Assistente de Meta, uma aplicação web que utiliza o poder da Inteligência Artificial do Google para fornecer dicas, estratégias e builds para seus jogos favoritos.

## 🚀 Sobre o Projeto

Este projeto foi criado como parte do evento NLW (Next Level Week) da Rocketseat, com o objetivo de construir uma ferramenta prática que integra uma interface web moderna com um modelo de linguagem avançado (LLM). O assistente foi projetado para ser um especialista em jogos como **Valorant**, **League of Legends** e **CS:GO**, respondendo a perguntas dos usuários de forma rápida e precisa.

### ✨ Funcionalidades

* **Seleção de Jogo:** Escolha para qual jogo você deseja a dica (Valorant, LoL, CS:GO).
* **Interação com IA:** Faça uma pergunta em linguagem natural sobre estratégias, builds de personagens/agentes, ou dicas gerais.
* **Respostas em Tempo Real:** A IA, potencializada pelo modelo **Gemini 2.0 Flash**, busca informações atualizadas para fornecer respostas relevantes ao meta atual do jogo.
* **Interface Limpa e Responsiva:** Interface amigável e direta, construída com HTML, CSS e JavaScript.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e ferramentas:

* **Frontend:**
    * **HTML5:** Estrutura semântica da aplicação.
    * **CSS3:** Estilização moderna, incluindo gradientes, animações e design responsivo.
    * **JavaScript (ES6+):** Manipulação do DOM, lógica da aplicação e comunicação com a API.

* **Inteligência Artificial:**
    * **Google Gemini 2.0 Flash:** Modelo de linguagem utilizado para gerar as respostas. A interação é feita via chamadas à sua API REST.
    * **Google Search Function Calling:** Ferramenta integrada ao Gemini que permite ao modelo realizar pesquisas na web para obter dados atualizados antes de responder.

* **Bibliotecas e APIs:**
    * **Showdown.js:** Biblioteca para converter a saída em Markdown da IA para HTML, permitindo uma formatação de texto rica.
    * **Google Fonts:** Para a tipografia da interface (fonte "Inter").

## ⚙️ Como Executar

Para executar este projeto localmente, você precisará de uma chave de API do Google Gemini.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/Leandro0919-maker/E-sport)
    ```

2.  **Abra o arquivo `index.html`:**
    * Navegue até a pasta do projeto e abra o arquivo `index.html` em seu navegador de preferência.

3.  **Configure a Chave de API:**
    * Obtenha sua chave de API no [Google AI Studio](https://aistudio.google.com/app/apikey).
    * Na página da aplicação, cole sua chave de API no campo "Informe a API KEY do Gemini".

4.  **Comece a usar!**
    * Selecione o jogo, digite sua pergunta e clique em "Perguntar".

## 👨‍💻 O que aprendi

* **Integração com APIs de IA:** Como estruturar e realizar chamadas `fetch` para a API do Google Gemini, enviando `prompts` complexos e tratando as respostas.
* **Engenharia de Prompt:** A importância de criar um "prompt de sistema" bem definido para guiar o comportamento da IA, estabelecendo regras, contexto e formato de saída.
* **Manipulação Assíncrona em JS:** Uso de `async/await` para gerenciar as chamadas de API e atualizar a interface de forma não bloqueante.
* **Desenvolvimento Frontend Moderno:** Práticas de HTML, CSS e JavaScript para criar uma experiência de usuário agradável e funcional.

---
Feito com ❤️ por [Leandro Velasquez](www.linkedin.com/in/jerson-leandro)