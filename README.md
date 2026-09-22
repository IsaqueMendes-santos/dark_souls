<!-- Banner Principal com a Imagem que você enviou -->
<div align="center">
  <img src="LINK_DA_SUA_IMAGEM_AQUI" alt="Dark Souls Logo" width="100%" style="max-width: 800px; margin-bottom: 20px;" />
  
  <h3>A HISTÓRIA — Um mundo de sombras e cinzas criado por FromSoftware</h3>
  
  <p align="center">
    <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-000000?style=for-the-badge&logo=github&logoColor=white" alt="Status" />
    <img src="https://img.shields.io/badge/Vers%C3%A3o-1.0.0-1a1a1a?style=for-the-badge&logo=git&logoColor=white" alt="Versão" />
    <img src="https://img.shields.io/badge/Licen%C3%A7a-MIT-333333?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="Licença" />
    <img src="https://img.shields.io/badge/Idioma-PT--BR-ffffff?style=for-the-badge&logo=googletranslate&logoColor=black" alt="Idioma" />
  </p>

  <p align="center">
    <a href="#-sobre-o-projeto">Sobre</a> •
    <a href="#-funcionalidades">Funcionalidades</a> •
    <a href="#-design-system">Design System</a> •
    <a href="#-tecnologias">Tecnologias</a> •
    <a href="#-instalação">Instalação</a> •
    <a href="#-estrutura-de-pastas">Estrutura</a> •
    <a href="#-autor">Autor</a>
  </p>
</div>

---

## Sobre o Projeto

> *"No princípio, o mundo era informe, coberto por névoa e árvores gigantes. Mas então veio o Fogo, trazendo a Disparidade."*

Este projeto é uma **experiência web imersiva e narrativa** que reconta a lore de *Dark Souls*. Muito além de um site estático, trata-se de um estudo de caso em **UI/UX temática**, onde cada elemento visual foi desenhado para transportar o usuário para dentro do universo sombrio de Lordran.

O objetivo principal foi criar uma interface que simula a leitura de um **tomo antigo** ou um **menu de jogo**, utilizando navegação paginada, tipografia clássica e um tratamento de imagem monocromático de alto contraste.

<div align="center">
  <!-- Se você tiver um GIF do site funcionando, coloque aqui. Senão, pode remover esta linha -->
  <img src="https://raw.githubusercontent.com/seu-usuario/dark-souls-historia/main/assets/preview.gif" alt="Preview do Projeto" width="800px" />
</div>

---

## Funcionalidades

O projeto está dividido em capítulos narrativos, cada um com sua própria identidade visual e conteúdo:

| Capítulo | Descrição | Destaques |
| :--- | :--- | :--- |
| **Capa (A História)** | A introdução ao mundo e o convite para a jornada. | Hero section com ilustração de cavaleiro e botão "Próxima Página". |
| **O Início da Chama** | A Era do Fogo e o surgimento dos Lords das Almas. | Galeria em grid 2x2 com retratos de Nito, Bruxa de Izalith, Gwyn e o Rei Caído. |
| **A Maldição dos Mortos-Vivos** | O declínio da Chama e o sacrifício de Gwyn. | Layout textual focado na leitura + imagem de cenário icônico (Anor Londo/Firelink). |
| **O Ciclo Eterno** | A decisão final do Escolhido e a inevitabilidade do ciclo. | Grid de ícones temáticos e texto de conclusão. |

---

## Design System

Este projeto não usa apenas "cores", ele usa uma **atmosfera**. O Design System foi construído para evocar a solidão e a grandiosidade do jogo.

### Paleta de Cores
| Cor | Hex | Uso |
| :---: | :---: | :--- |
| **Preto Profundo** | `#0A0A0A` | Fundo principal (Background) |
| **Branco Osso** | `#E0E0E0` | Títulos e Textos Principais |
| **Cinza Ardósia** | `#888888` | Subtítulos e Textos Secundários |
| **Cinza Carvão** | `#1A1A1A` | Bordas e Botões |

### Tipografia
*   **Títulos:** `Cinzel` — *Serifada clássica, evoca inscrições antigas e épicas.*
*   **Corpo:** `Lato` — *Sans-serif limpa para garantir legibilidade em blocos de texto densos.*

### Tratamento de Imagem
Todas as ilustrações passaram por um processo de **High Contrast / Noir**, utilizando `filter: grayscale(100%) contrast(1.1)` para simular arte conceitual antiga ou gravuras.

---

## Tecnologias Utilizadas

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</div>

*   **Front-end:** HTML5 semântico e CSS3 (Flexbox/Grid para o layout responsivo).
*   **Interatividade:** Navegação entre páginas estáticas (pode ser evoluído para SPA com JS).
*   **Design:** Prototipagem e edição de imagens.
*   **Versionamento:** Git e GitHub.

---

## Instalação e Uso

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/dark-souls-historia.git
