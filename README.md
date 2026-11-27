# 🛒 Ramazom

> Online shopping website — full stack learning project (current phase: front-end base).

---

## 📌 About the project

**Ramazom** is a fictional e-commerce site built as part of my journey learning **full stack development**. The initial focus is on the **front-end**, building the base structure (HTML + CSS) and **marking placeholder spots** where the following will eventually go:

- **API** integration
- **Database** consumption
- **Bootstrap** componentization
- Dynamic logic with **JavaScript**

At this stage, visual elements are just "markers" (boxes, containers, buttons) to represent where real components will appear. Styling is simple and temporary — colors like `brown`, `darkorange`, and `antiquewhite` are only there to visualize the structure.

---

## 🎯 Goal

Practice building e-commerce layouts, organize HTML/CSS files, and prepare a solid base to integrate back-end technologies and frameworks in the future.

---

## 📁 File structure

Ramazom/
│
├── index.html # Home page (logged-in user)
├── homeWtLog.html # Home page (visitor / not logged in)
├── logIn.html # Login / sign-up page
├── myCart.html # Shopping cart page
│
└── Styles/
├── Index.css # Home styles (logged-in user)
├── homeWtLog.css # Home styles (visitor)
├── logIn.css # Login page styles
└── myCart.css # Cart page styles

---

## 📄 Implemented pages

### 🏠 `index.html` — Home (Logged-in user)
- Top menu: **Meu Carrinho**, **Para Você**, **Ofertas Imperdíveis**, **Minha conta**
- Search field + "Pesquisar" button
- Three product rows (4 `product_Box` per row) — **placeholders** for real products
- CSS: `Styles/Index.css`

### 🏠 `homeWtLog.html` — Home (Visitor)
- Top menu: **Meu Carrinho**, **Ofertas Imperdíveis**, **Login**
- Search field + "Pesquisar" button
- Same grid of placeholder products
- CSS: `Styles/homeWtLog.css`

### 🔐 `logIn.html` — Login / Sign-up
- Top menu with "Tela Inicial" button
- Central container (`login_Container`) reserved for the login/sign-up form
- CSS: `Styles/logIn.css`

### 🛍️ `myCart.html` — Cart
- Top menu with "Voltar para Home" button
- Product list (`products`) — placeholder
- **"Comprar"** button (reserved for checkout logic)
- CSS: `Styles/myCart.css`

---

## 🧱 Visual structure (placeholders)

- `product_Box` → placeholder for **product cards**
- `products` → placeholder for **cart items**
- `login_Container` → placeholder for **authentication form**
- `buy_products` → placeholder for **order summary and checkout**

> ⚠️ All these elements will be replaced by dynamic components once APIs, the database, and Bootstrap are integrated.

---

## 🛠️ Planned technologies

| Layer          | Status           | Technology                     |
|----------------|------------------|--------------------------------|
| Front-end base | ✅ In progress    | HTML5, CSS3                    |
| Front-end UI   | 🔜 Planned        | Bootstrap                      |
| Interactivity  | 🔜 Planned        | JavaScript                     |
| Back-end       | 🔜 Planned        | APIs (TBD)                     |
| Database       | 🔜 Planned        | (TBD)                          |

---

## 🚧 Next steps

- [ ] Add Bootstrap for responsive layout
- [ ] Implement JavaScript for interactions (search, cart, login)
- [ ] Create product and user APIs
- [ ] Integrate database
- [ ] Implement authentication (login/sign-up)
- [ ] Replace placeholders with real data
- [ ] Refine color palette and visual identity

---

## 👨‍💻 Author

Developed by a **full stack** student in the learning process, starting with the front-end and gradually evolving toward the back-end.

---

## 📜 License

Study project — free to consult and learn from.