# 📝 Quiz Interativo para Programadores

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Um web app interativo de perguntas e respostas projetado especificamente para testar conhecimentos de lógica e desenvolvimento web. O projeto foca no uso avançado de formulários semânticos, acessibilidade e estilização moderna com variáveis de fontes externas.

---

## 🚀 Funcionalidades e Estrutura

O quiz foi planejado para explorar múltiplos formatos de interação em uma única página:
* **Variedade de Inputs:** Uso de campos de texto, senhas ocultas, seletores de data, checkboxes de múltipla escolha, botões de rádio e upload de arquivos.
* **Componentes Nativos:** Implementação do elemento `<details>` e `<summary>` para revelar o gabarito dinamicamente sem necessidade de scripts complexos.
* **Acessibilidade:** Uso correto de tags `<abbr>` com títulos explicativos para acrônimos técnicos (como HTML e CSS).
* **Seção de Feedback:** Formulário completo com `<fieldset>` e `<legend>` para captura estruturada de comentários do usuário.

---

## 🎨 Design e Identidade Visual (CSS)

A estilização foi criada do zero com foco em uma experiência de leitura confortável, importando a fonte **Cabin** via Google Fonts e utilizando um contraste sofisticado entre tons terrosos e verdes:

| Elemento | Cor Hexadecimal | Amostra | Função no Layout |
| :--- | :---: | :--- | :--- |
| **Fundo Principal** | `#F4F0EA` | ⬜ Areia Claro | Contraste de fundo limpo |
| **Headers & Footers** | `#331F19` | 🟫 Marrom Escuro | Blocos de destaque e estrutura |
| **Destaques & Bordas** | `#CCD595` | 🟩 Verde Oliva Claro | Inputs, tabelas e botões ativos |
| **Textos Secundários** | `#798252` | 🟩 Verde Musgo | Leitura de parágrafos |

---

## 📂 Organização dos Arquivos

```packages
📂 quiz-programadores
├── 📄 index.html      # Estrutura semântica do quiz, tabelas e formulários
├── 📄 sobremim.html   # Página secundária de perfil do autor
├── 🎨 style.css       # Reset global, tipografia (Cabin) e design responsivo
└── 📂 assets/         # Recursos de mídia da aplicação
    └── 🖼️ imagem.png  # Logotipo utilizado na questão 8
