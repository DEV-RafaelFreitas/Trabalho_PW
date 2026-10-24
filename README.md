# OverHub

> Trabalho de **Programação Web 1 (PW1)**, Senac São Paulo.
> Site multipágina feito com **HTML, CSS e JavaScript puros**, usando `localStorage` para guardar os dados.

<!-- PREENCHER: 2 ou 3 frases sobre a ideia do site (o que é, para quem, o que a pessoa consegue fazer nele). -->
**Sobre o projeto:** [descreva aqui a ideia do OverHub]

---

## Status do projeto

| Página / recurso | Status |
|---|---|
| Tela de login (HTML e CSS) | Pronto |
| Login com JavaScript (conferir usuário no `localStorage`) | A fazer |
| Cadastro de usuário | A fazer |
| Página inicial (menu, logo e apresentação do site) | A fazer |
| Páginas de conteúdo (produtos, carrinho, etc.) | A fazer |
| Adição e remoção de itens (`localStorage`) | A fazer |
| Relatório do que está armazenado | A fazer |

## Requisitos do trabalho

- [ ] Site com **no mínimo 5 páginas** ligadas pelo menu
- [ ] Formulário de **login e cadastro**
- [ ] **Adicionar e remover** elementos usando `localStorage`
- [ ] **Relatório** do que está armazenado no `localStorage`
- [ ] **Manipulação do DOM** com JavaScript
- [ ] Página inicial com **menu**, informação sobre o site e um **logo**
- [ ] JavaScript usado também em outras partes, além do `localStorage`
- [ ] **Todas as páginas estilizadas**
- [ ] Responsividade (diferencial)

## Tecnologias

- **HTML5**: estrutura das páginas
- **CSS3**: estilização (Flexbox, variáveis CSS)
- **JavaScript**: lógica, manipulação do DOM e `localStorage`
- Fonte [Kode Mono](https://fonts.google.com/specimen/Kode+Mono) (Google Fonts)

## Estrutura de pastas

```
trabalho-pw1/
├── login.html
├── css/
│   └── login.css
├── icons/              # ícones SVG (Google, GitHub, LinkedIn, usuário)
└── README.md
```

> As demais páginas, a pasta `js/` e o `global.css` (estilos compartilhados) entram conforme o projeto avança.

## Como executar

Não precisa instalar nada.

1. Baixe ou clone o repositório:
   ```bash
   git clone <URL-DO-REPOSITORIO>
   ```
2. Abra o arquivo `login.html` no navegador (dois cliques).

Dica: no VS Code, a extensão **Live Server** recarrega a página sozinha a cada alteração salva.

## Design

O layout foi criado no Figma: [link do protótipo](#) <!-- PREENCHER com o link do Figma -->

Cores principais da interface:

| Uso | Cor |
|---|---|
| Fundo da página | `#01010d` |
| Laranja de destaque | `#ff7900` |
| Laranja dos botões | `#ff6200` |
| Botão escuro | `#1a005b` |
| Link "Esqueceu sua senha" | `#cc7629` |

## Fluxo de trabalho em grupo

1. Cada funcionalidade é desenvolvida em uma **branch própria**, saindo da `main`:
   ```bash
   git checkout main
   git pull origin main
   git checkout -b feature/nome-da-funcionalidade
   ```
2. Os commits seguem o formato `tipo(área): descrição`, por exemplo `feat(login): adiciona tela de login`.
3. O código sobe para a branch e é aberto um **Pull Request** para a `main`.
4. Depois da aprovação de outro integrante, é feito o **merge**.

## Integrantes

| Nome | GitHub | Responsabilidade |
|---|---|---|
| [Nome] | [@usuario] | [ex.: tela de login] |
| [Nome] | [@usuario] | [ex.: cadastro] |
