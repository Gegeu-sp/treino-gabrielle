# 🏋️‍♀️ Web App de Treinos Personalizados

> **Aluna:** Gabrielle Mantovani  
> **Mentoria:** Argeu Rodrigues  
> **Status:** Concluído ✅

Este projeto consiste no desenvolvimento de uma **Single Page Application (SPA)** focada na experiência do usuário para acompanhamento de rotinas de treinamento físico. O objetivo foi criar uma interface mobile-first, performática e livre de frameworks pesados, demonstrando domínio sobre as tecnologias fundamentais da web.

## 1. Objetivo do Projeto

O objetivo principal deste exercício foi projetar e implementar uma solução digital que substitua as planilhas de treino convencionais (PDF/Excel) por uma aplicação interativa e responsiva. A aplicação deve permitir:
*   Visualização clara da rotina de exercícios.
*   Marcação de progresso em tempo real (checklists).
*   Acesso a detalhes técnicos de execução (modal dinâmico).
*   Registro histórico de frequência (gamificação básica).

## 2. Passos da Execução

O desenvolvimento foi realizado seguindo um fluxo incremental:

1.  **Estruturação Semântica (HTML5)**:
    *   Criação do esqueleto da aplicação com tags semânticas (`<header>`, `<main>`, `<section>`, `<nav>`).
    *   Definição de metadados SEO para indexação correta.

2.  **Estilização Responsiva (TailwindCSS)**:
    *   Implementação de design mobile-first.
    *   Uso de classes utilitárias para layout (Flexbox/Grid), espaçamento e tipografia.
    *   Personalização da paleta de cores (`rose-500` como cor primária) para identidade visual.

3.  **Lógica de Interação (JavaScript ES6+)**:
    *   Criação de estrutura de dados JSON para armazenar os treinos e detalhes.
    *   Desenvolvimento de funções de renderização dinâmica (`renderList`).
    *   Implementação de persistência de dados local (`localStorage`) para salvar o histórico do usuário.
    *   Criação de Modais Dinâmicos para exibir detalhes dos exercícios sem recarregar a página.

4.  **Refinamento e UX**:
    *   Adição de feedback visual (animação de confetti).
    *   Melhoria na acessibilidade e usabilidade em dispositivos móveis.

## 3. Requisitos Técnicos

Para a execução deste projeto, foram utilizadas as seguintes tecnologias e conceitos:

*   **Linguagens**: HTML5, CSS3, JavaScript (Vanilla).
*   **Framework CSS**: TailwindCSS (via CDN).
*   **Armazenamento**: LocalStorage API.
*   **Controle de Versão**: Git.
*   **Conceitos Aplicados**:
    *   DOM Manipulation.
    *   Event Delegation.
    *   JSON Data Structure.
    *   Mobile-First Design.

## 4. Critérios de Avaliação

O sucesso do projeto é medido pelos seguintes critérios:

*   **Funcionalidade**: O app deve permitir marcar exercícios, salvar histórico e visualizar detalhes sem erros.
*   **Responsividade**: A interface deve se adaptar perfeitamente a telas de smartphones e desktops.
*   **Qualidade de Código**: Código limpo, bem indentado e com variáveis descritivas (Clean Code).
*   **Performance**: Carregamento instantâneo e transições suaves entre abas.
*   **Independência**: O app deve funcionar sem necessidade de instalação de dependências complexas (npm/node_modules) para rodar localmente.

## 5. Formato para Submissão

O projeto deve ser entregue via repositório no **GitHub**, contendo:

1.  **Código Fonte**: Todos os arquivos necessários (`index.html`, assets se houver).
2.  **README.md**: Este arquivo de documentação técnica.
3.  **Histórico de Commits**: Demonstrando a evolução do desenvolvimento.

---

*Projeto desenvolvido como parte do portfólio de Engenharia de Software e Desenvolvimento Web.*
