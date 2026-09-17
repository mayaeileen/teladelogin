# 🔐 Tela de Login Interativa

Uma interface de tela de login e cadastro moderna, acessível e totalmente responsiva, desenvolvida com tecnologias web fundamentais (HTML5, CSS3 e JavaScript). Este projeto traz foco na usabilidade, experiência do usuário (UI/UX) e boas práticas de código front-end.

---

## 📑 Sumário

- [📌 Visão Geral e Recursos](#-visão-geral-e-recursos)
- [👤 O que os Usuários Podem Fazer](#-o-que-os-usuários-podem-fazer)
- [⌨️ Atalhos de Teclado e Acessibilidade](#️-atalhos-de-teclado-e-acessibilidade)
- [🛠️ Como Construí](#️-como-construí)
- [💡 O que Aprendi](#-o-que-aprendi)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🔮 O que Pode Ser Melhorado](#-o-que-pode-ser-melhorado)
- [👩‍💻 Autora](#-autora)

---

## 📌 Visão Geral e Recursos

- **Design Moderno:** Interface limpa com paleta de cores harmoniosa, sombras suaves e efeitos de foco.
- **Totalmente Responsivo:** Layout fluido que se adapta perfeitamente a dispositivos móveis, tablets e telas de computador.
- **Animações e Transições:** Feedback visual nas interações (hover em botões, foco em campos e mensagens de erro/sucesso).
- **Validação de Formulários:** Verificação em tempo real do formato dos dados inseridos.

---

## 👤 O que os Usuários Podem Fazer

1. **Inserir Credenciais:** Digitar e-mail/nome de usuário e senha nos campos correspondentes.
2. **Alternar Visibilidade da Senha:** Clicar no ícone de "olho" para exibir ou ocultar os caracteres da senha.
3. **Alternar entre Login e Cadastro:** Alternar de forma fluida entre o formulário de login e o formulário de registro sem recarregar a página.
4. **Enviar o Formulário:** Submeter os dados informados via clique no botão ou pressionando a tecla `Enter`.
5. **Navegar por Teclado:** Utilizar a tecla `Tab` para percorrer todos os elementos interativos na ordem correta.

---

## ⌨️ Atalhos de Teclado e Acessibilidade

O projeto foi pensado para ser navegável via teclado para garantir uma melhor acessibilidade:

| Tecla / Atalho | Ação |
| :--- | :--- |
| **`Tab`** | Avança para o próximo campo de texto, botão ou link da tela. |
| **`Shift` + `Tab`** | Retorna ao campo ou elemento anterior. |
| **`Enter`** | Submete o formulário quando o foco está em um dos campos de texto ou no botão de envio. |
| **`Space` (Espaço)** | Ativa botões ou alterna a visibilidade de senha quando o foco está no ícone correspondente. |

---

## 🛠️ Como Construí

A estrutura do projeto foi desenvolvida utilizando exclusivamente web standards puras (Vanilla Web Stack), sem dependência de frameworks externos:

1. **HTML5:** 
   - Utilização de tags semânticas (`<main>`, `<form>`, `<section>`, `<label>`, `<button>`) para garantir estrutura lógica e suporte a leitores de tela.
   - Aplicação dos atributos de tipo corretos (`type="email"`, `type="password"`, `required`).

2. **CSS3:**
   - Construção do layout utilizando **Flexbox** e **CSS Grid** para centralização perfeita e fluidez.
   - Uso de variáveis CSS (`--primary-color`, `--bg-color`, etc.) para manter consistência e facilitar a manutenção do tema.
   - Aplicação de `@media` queries para garantir responsividade em diferentes resoluções.

3. **JavaScript (ES6+):**
   - Manipulação do DOM para capturar eventos de envio (`submit`), digitação (`input`) e clique (`click`).
   - Implementação da lógica para alternar o tipo do campo de senha (`type="password"` ↔ `type="text"`).
   - Validação de expressões regulares (RegEx) para formato de e-mail e força da senha.

---

## 💡 O que Aprendi

Durante o desenvolvimento deste projeto, aprofundei meus conhecimentos em:

- **Manipulação Avançada do DOM:** Como interagir com elementos HTML usando JavaScript puro de forma limpa e otimizada.
- **Acessibilidade Web (a11y):** A importância da navegação por teclado, uso correto do foco e contraste de cores adequado.
- **UX no Preenchimento de Formulários:** Entendimento de como mensagens de erro claras e validação imediata reduzem a frustração do usuário.
- **Organização de Código:** Estruturação de CSS modular e reutilizável através de variáveis.

---

## 🚀 Como Executar o Projeto

Não é necessário instalar gerenciadores de pacotes (como npm/yarn) ou configurar servidores locais complexos.

### Pré-requisitos
Apenas um navegador web atualizado (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).

### Passo a Passo

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/mayaeileen/teladelogin.git](https://github.com/mayaeileen/teladelogin.git)

