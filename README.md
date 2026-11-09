# Biblioteca-Musical-Luigi 🎵  Gestão e Acervo Musical

> **Projeto Prático de Fim de Semestre**  
> Aplicação Web desenvolvida para gerenciamento, cadastro e visualização de artistas e faixas musicais.

---

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)


---

## 📌 Sumário

- [Visão Geral](#-visão-geral)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Mapeamento de Páginas](#-mapeamento-de-páginas)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Próximos Passos & Melhorias](#-próximos-passos--melhorias)
- [Autores e Contribuição](#-autores-e-contribuição)

---

## 🔍 Visão Geral

O **SoundHub** é um sistema web front-end concebido para simular uma plataforma completa de gerenciamento musical. O projeto abrange desde a autenticação de usuários até o cadastro refinado de artistas, faixas e a exibição centralizada do catálogo.

---

## ✨ Funcionalidades Principais

- [x] **Autenticação:** Tela de login responsiva para controle de acesso.
- [x] **Dashboard Central:** Navegação fluida entre todas as seções da aplicação.
- [x] **Gestão de Artistas:** Formulário estruturado para registro de cantores, bandas e bandas independentes.
- [x] **Gestão de Músicas:** Formulário dedicado para inclusão de faixas, álbuns e gêneros.
- [x] **Catálogo Interativo:** Listagem de faixas cadastradas para fácil consulta.
- [x] **Design Responsivo:** Interface padronizada através de um único arquivo de estilos (`style.css`).

---

## 📁 Estrutura do Projeto

```text
Site de fim de semestre/
│
├── 📄 index.html              # Dashboard e visualização principal
├── 🔑 login.html              # Tela de entrada e autenticação
├── 👤 cadastro_artista.html   # Formulário de novos artistas
├── 🎶 cadastro.musica.html    # Formulário de novas músicas
├── 📜 listagem_musicas.html   # Tabela e catálogo de faixas
└── 🎨 style.css               # Estilização global do sistema
```

---

## 🗺️ Mapeamento de Páginas

| Arquivo | Função | Descrição |
| :--- | :--- | :--- |
| `login.html` | Autenticação | Formulário de entrada para validar o acesso do usuário. |
| `index.html` | Início | Painel principal com atalhos para todas as áreas do sistema. |
| `cadastro_artista.html` | Cadastro | Entrada de dados de novos artistas (nome, gênero, biografia). |
| `cadastro.musica.html` | Cadastro | Entrada de dados de novas faixas (título, artista, duração, álbum). |
| `listagem_musicas.html` | Consulta | Exibição organizada do acervo musical cadastrado. |
| `style.css` | Estilos | Regras visuais, paleta de cores e responsividade global. |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Marcação semântica para acessibilidade e boa estrutura.
- **CSS3:** Flexbox/Grid para layouts limpos, transições e responsividade.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Não é necessária a instalação de servidores ou compilers. Apenas um navegador web moderno (Google Chrome, Firefox, Edge, Safari).

### Passo a Passo

1. **Clonar ou Baixar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. **Navegar até a pasta do projeto:**
   ```bash
   cd "Site de fim de semestre"
   ```
3. **Executar a aplicação:**
   - Dê um duplo clique no arquivo `login.html` ou `index.html`.
   - Alternativamente, use a extensão **Live Server** no VS Code para uma melhor experiência de desenvolvimento.

---

## 🔮 Próximas Melhorias

- [ ] Integração com **JavaScript (ES6+)** para manipulação do DOM e validação de formulários no cliente.

---

## 🤝 Autores e Contribuição

Desenvolvido como projeto de avaliação final de semestre.

Se quiser contribuir com melhorias:
1. Faça um **Fork** do projeto.
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaFeature`).
3. Abra um **Pull Request**.

---
<p center align="center">
  Feito com ❤️ para o encerramento do semestre letivo!
</p>
