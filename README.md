# 🏋️‍♀️ Treinos Personalizados - Web App

> **Personal Trainer:** Argeu Rodrigues  
> **Aluna:** Gabrielle Mantovani

Este é um projeto de estudo e aplicação real de um **Web App de Treinos** (Single Page Application) desenvolvido com tecnologias web modernas e leves. O objetivo é fornecer uma interface elegante, rápida e funcional para acompanhamento de rotinas de musculação.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído seguindo o princípio **KISS (Keep It Simple, Stupid)**, evitando complexidade desnecessária de frameworks pesados para um caso de uso simples.

*   **HTML5 Semântico**: Estrutura base da aplicação.
*   **TailwindCSS (via CDN)**: Framework de estilização utility-first para design rápido e responsivo.
*   **JavaScript (Vanilla ES6+)**: Lógica de interação, manipulação de DOM e gerenciamento de estado local.
*   **LocalStorage**: Banco de dados no navegador para persistir o histórico de treinos e streaks sem precisar de backend.
*   **Chart.js**: Biblioteca para renderização dos gráficos de progresso.
*   **Canvas Confetti**: Efeito visual de celebração ao concluir treinos.
*   **FontAwesome**: Ícones vetoriais.

## 📂 Estrutura do Projeto

O projeto é monólito em um único arquivo (`index.html`) para facilitar o deploy e compartilhamento rápido, mas internamente é organizado como um código modular:

*   **`<head>`**: Metadados de SEO, importação de fontes (Lato & Playfair Display) e bibliotecas.
*   **`<style>`**: Customizações CSS específicas que o Tailwind não cobre (animações, scrollbars).
*   **`<body>`**:
    *   **Header**: Identificação e branding.
    *   **Main**: Área de conteúdo dinâmico (troca entre visualização de Treinos e Estatísticas).
    *   **Modais**: Componentes de interface (Sucesso e Detalhes do Exercício) que ficam ocultos até serem acionados.
    *   **Script**: Contém toda a lógica de negócios:
        *   `workouts`: Objeto JSON contendo a "base de dados" dos exercícios.
        *   `renderList()`: Função que gera o HTML dos cards de treino dinamicamente.
        *   `openExerciseModal()`: Função de *Lazy Loading* que injeta os detalhes do exercício apenas quando solicitado.
        *   `finishWorkout()`: Lógica de gamificação e salvamento de dados.

## 🇫🇷 Vocabulário de Treino (Francês/Português)

Como parte do estudo de idiomas integrado ao treino, os exercícios foram traduzidos para o Francês:

| Francês | Português |
|---------|-----------|
| **Squat Libre** | Agachamento Livre |
| **Soulevé de Terre** | Levantamento Terra |
| **Développé Couché/Incliné** | Supino Reto/Inclinado |
| **Fente** | Afundo / Passada |
| **Gainage** | Prancha (Isometria) |
| **Tirage Poitrine** | Puxada Alta |
| **Relevé de Bassin** | Elevação Pélvica |

## 🚀 Como Executar

1.  **Clone o repositório**:
    ```bash
    git clone https://github.com/seu-usuario/treinos-consultoria.git
    ```
2.  **Abra o arquivo**:
    Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, Safari). Não é necessário instalar Node.js ou rodar servidores locais.

## 📱 Mobile First

O layout foi pensado primeiramente para celulares, funcionando como um **App Nativo** quando adicionado à tela inicial (Web App Manifest ready).

---

*Desenvolvido com ❤️ e Código Limpo.*
