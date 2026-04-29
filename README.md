# 🎬 CineGold — Site de Cinema

Site de cinema desenvolvido como projeto escolar, exibindo filmes favoritos com cards, página de contato e sistema de compra de ingressos.

## 🔗 Links

- **Repositório:** _[cole o link do seu repositório aqui]_
- **Site publicado:** _[cole o link do GitHub Pages aqui]_

---

## 📋 Funcionalidades

- 🎥 **Vitrine de Filmes** — cards com pôster e título dos filmes em cartaz
- 🔍 **Filtro e Busca** — busca por nome e filtro por gênero
- 🎞️ **Página do Filme** — sinopse, elenco, diretor e sessões disponíveis
- 💺 **Seleção de Assentos** — mapa interativo da sala de cinema
- 🛒 **Compra de Ingresso** — fluxo completo de seleção e pagamento
- 📬 **Página de Contato** — formulário com Nome, E-mail e Mensagem
- ✅ **Validação de Formulário** — campos obrigatórios com feedback visual

---

## 🎬 Filmes em Cartaz

| Poster | Título | Gênero |
|--------|--------|--------|
| ![Avengers](https://media.base44.com/images/public/69e9f558fcced3fc16b04722/908079fc8_image.png) | **The Avengers** | Ação / Super-herói |
| ![Backrooms](https://media.base44.com/images/public/69e9f558fcced3fc16b04722/1c65a2df3_image.png) | **The Backrooms** | Terror / Horror |
| ![Spider-Man](https://media.base44.com/images/public/69e9f558fcced3fc16b04722/5f6edb30b_image.png) | **Spider-Man: Brand New Day** | Ação / Super-herói |

---

## 🛠️ Tecnologias Utilizadas

- **React** — biblioteca para construção da interface
- **Tailwind CSS** — estilização com classes utilitárias
- **Framer Motion** — animações suaves
- **React Router DOM** — navegação entre páginas
- **Lucide React** — ícones
- **Vite** — bundler e servidor de desenvolvimento

---

## 🎨 Design

- Tema escuro com paleta inspirada em cinema (preto, dourado e âmbar)
- Tipografia: **Playfair Display** (títulos) + **Inter** (corpo)
- Layout responsivo para desktop e mobile
- Cards organizados em grid com flexbox/grid CSS

---

## 📁 Estrutura do Projeto

```
src/
├── pages/
│   ├── Home.jsx          # Página principal com vitrine de filmes
│   ├── Movies.jsx        # Listagem com busca e filtros
│   ├── MovieDetails.jsx  # Detalhes do filme e sessões
│   ├── BuyTicket.jsx     # Seleção de assentos e pagamento
│   ├── MyTickets.jsx     # Meus ingressos
│   └── Contact.jsx       # Formulário de contato
├── components/
│   └── cinema/
│       ├── Navbar.jsx        # Barra de navegação
│       ├── Footer.jsx        # Rodapé
│       ├── HeroSection.jsx   # Banner principal
│       ├── MovieCard.jsx     # Card de filme
│       ├── SeatSelector.jsx  # Seletor de assentos
│       └── Layout.jsx        # Layout base
├── lib/
│   └── moviesData.js     # Dados dos filmes
└── App.jsx               # Rotas da aplicação
```

---

## ▶️ Como rodar localmente

```bash
# Instalar dependências
npm install

# Rodar em desenvolvimento
npm run dev

# Build para produção
npm run build
```

---

## 👤 Autor

**[Seu Nome]** — Projeto Escolar de Desenvolvimento Web

---

> 🍿 *"O cinema é um espelho que reflete a vida."*
