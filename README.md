# 🛒 Ramazom

> Site de vendas online — projeto de estudo em desenvolvimento full stack (fase atual: front-end base).
>
> *Online shopping website — full stack learning project (current phase: front-end base).*

---

## 📌 Sobre o projeto / About the project

**PT:** **Ramazom** é um e-commerce fictício criado como parte da minha jornada de aprendizado em **desenvolvimento full stack**. O foco inicial é no **front-end**, construindo a estrutura base (HTML + CSS) e **marcando os espaços reservados** onde, futuramente, entrarão: integração com **APIs**, consumo de **banco de dados**, componentização com **Bootstrap** e lógica dinâmica com **JavaScript**. Nesta fase, os elementos visuais são apenas "marcas" para representar onde os componentes reais irão surgir. A estilização é simples e provisória.

**EN:** **Ramazom** is a fictional e-commerce site built as part of my journey learning **full stack development**. The initial focus is on the **front-end**, building the base structure (HTML + CSS) and **marking placeholder spots** where **API** integration, **database** consumption, **Bootstrap** componentization, and dynamic **JavaScript** logic will eventually go. At this stage, visual elements are just "markers" to represent where real components will appear. Styling is simple and temporary.

---

## 🎯 Objetivo / Goal

**PT:** Praticar a construção de layouts de e-commerce, organizar arquivos HTML/CSS e preparar uma base sólida para integrar tecnologias back-end e frameworks no futuro.

**EN:** Practice building e-commerce layouts, organize HTML/CSS files, and prepare a solid base to integrate back-end technologies and frameworks in the future.

---

## 📁 Estrutura de arquivos / File structure

Ramazom/
│
├── index.html # Home (usuário logado) / Home (logged-in user)
├── homeWtLog.html # Home (visitante) / Home (visitor)
├── logIn.html # Login / cadastro — Login / sign-up
├── myCart.html # Carrinho — Shopping cart
│
└── Styles/
├── Index.css # Estilos da home (logado) — Home styles (logged-in)
├── homeWtLog.css # Estilos da home (visitante) — Home styles (visitor)
├── logIn.css # Estilos do login — Login styles
└── myCart.css # Estilos do carrinho — Cart styles

---

## 📄 Páginas implementadas / Implemented pages

### 🏠 `index.html` — Home (Usuário logado / Logged-in user)
- **PT:** Topo com menu: **Meu Carrinho**, **Para Você**, **Ofertas Imperdíveis**, **Minha conta**. Campo de busca + botão "Pesquisar". Três linhas de produtos (4 `product_Box` por linha) — **espaços reservados** para produtos reais.
- **EN:** Top menu: **Meu Carrinho**, **Para Você**, **Ofertas Imperdíveis**, **Minha conta**. Search field + "Pesquisar" button. Three product rows (4 `product_Box` per row) — **placeholders** for real products.
- CSS: `Styles/Index.css`

### 🏠 `homeWtLog.html` — Home (Visitante / Visitor)
- **PT:** Topo com menu: **Meu Carrinho**, **Ofertas Imperdíveis**, **Login**. Campo de busca + botão "Pesquisar". Mesma grade de produtos reservados.
- **EN:** Top menu: **Meu Carrinho**, **Ofertas Imperdíveis**, **Login**. Search field + "Pesquisar" button. Same grid of placeholder products.
- CSS: `Styles/homeWtLog.css`

### 🔐 `logIn.html` — Login / Cadastro — Login / Sign-up
- **PT:** Topo com botão "Tela Inicial". Container central (`login_Container`) reservado para o formulário de login/cadastro.
- **EN:** Top menu with "Tela Inicial" button. Central container (`login_Container`) reserved for the login/sign-up form.
- CSS: `Styles/logIn.css`

### 🛍️ `myCart.html` — Carrinho / Cart
- **PT:** Topo com botão "Voltar para Home". Lista de produtos (`products`) — reservado. Botão **"Comprar"** (reservado para lógica de checkout).
- **EN:** Top menu with "Voltar para Home" button. Product list (`products`) — placeholder. **"Comprar"** button (reserved for checkout logic).
- CSS: `Styles/myCart.css`

---

## 🧱 Estrutura visual (placeholders) / Visual structure (placeholders)

| Elemento / Element | Reservado para / Reserved for |
|---|---|
| `product_Box` | Cards de produto / Product cards |
| `products` | Itens no carrinho / Cart items |
| `login_Container` | Formulário de autenticação / Authentication form |
| `buy_products` | Resumo e finalização da compra / Order summary and checkout |

> ⚠️ **PT:** Todos esses elementos serão substituídos por componentes dinâmicos quando as APIs, o banco de dados e o Bootstrap forem integrados.
>
> **EN:** All these elements will be replaced by dynamic components once APIs, the database, and Bootstrap are integrated.

---

## 🛠️ Tecnologias previstas / Planned technologies

| Camada / Layer | Status | Tecnologia / Technology |
|---|---|---|
| Front-end base | ✅ Em andamento / In progress | HTML5, CSS3 |
| Front-end UI | 🔜 Planejado / Planned | Bootstrap |
| Interatividade / Interactivity | 🔜 Planejado / Planned | JavaScript |
| Back-end | 🔜 Planejado / Planned | APIs (a definir / TBD) |
| Banco de dados / Database | 🔜 Planejado / Planned | (a definir / TBD) |

---

## 🚧 Próximos passos / Next steps

- [ ] **PT:** Adicionar Bootstrap para layout responsivo — **EN:** Add Bootstrap for responsive layout
- [ ] **PT:** Implementar JavaScript para interações (busca, carrinho, login) — **EN:** Implement JavaScript for interactions (search, cart, login)
- [ ] **PT:** Criar API de produtos e usuários — **EN:** Create product and user APIs
- [ ] **PT:** Integrar banco de dados — **EN:** Integrate database
- [ ] **PT:** Implementar autenticação (login/cadastro) — **EN:** Implement authentication (login/sign-up)
- [ ] **PT:** Substituir placeholders por dados reais — **EN:** Replace placeholders with real data
- [ ] **PT:** Refinar paleta de cores e identidade visual — **EN:** Refine color palette and visual identity

---

## 👨‍💻 Autor / Author

**PT:** Desenvolvido por um estudante de **full stack** em processo de aprendizagem, começando pelo front-end e evoluindo gradualmente para o back-end.

**EN:** Developed by a **full stack** student in the learning process, starting with the front-end and gradually evolving toward the back-end.

---

## 📜 Licença / License

**PT:** Projeto de estudo — livre para consulta e aprendizado.

**EN:** Study project — free to consult and learn from.