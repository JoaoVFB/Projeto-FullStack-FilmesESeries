# 🎬 App de Filmes e Séries com Favoritos  

## 📌 Descrição  
Este projeto é um **SPA (Single Page Application)** desenvolvido em **React.js**, que consome a [TMDB API](https://developer.themoviedb.org/) para exibir informações sobre filmes e séries.  

O usuário pode:  
- 🔍 Buscar filmes/séries por título.  
- 📖 Visualizar detalhes como pôster, sinopse e nota de avaliação.  
- ⭐ Adicionar/remover filmes e séries à sua **lista de favoritos**.  

No futuro (**Parte 2 - Backend da disciplina**), o projeto será expandido para permitir:  
- 👤 **Cadastro e login de usuários**.  
- 💾 **Persistência de favoritos** em um banco de dados.  
- 🎯 **Recomendações personalizadas** com base no histórico.  

---

## 🚀 Tecnologias Utilizadas  

### **Frontend**  
- [React.js](https://react.dev/) — biblioteca principal para construção da interface  
- [Vite](https://vitejs.dev/) — ferramenta para build e desenvolvimento rápido  
- [Axios](https://axios-http.com/) — requisições HTTP para a API  
- [Material UI](https://mui.com/) — biblioteca de componentes visuais  

### **API JSON**  
- [TMDB API](https://developer.themoviedb.org/) — utilizada para obter dados de filmes e séries  

### **Hook/Funcionalidade React**  
- `useReducer` — gerenciamento do estado global da lista de favoritos  

### **Bibliotecas Externas**  
- [Material UI](https://mui.com/) — interface responsiva e moderna  
- [Axios](https://axios-http.com/) — consumo da API  
- [React Router](https://reactrouter.com/) *(opcional)* — rotas internas (detalhes de filmes/séries)  

---

## 📂 Estrutura do Projeto (inicial)  
```bash
📦 app-filmes-series
├── 📁 public
│   └── index.html
├── 📁 src
│   ├── 📁 components     # componentes reutilizáveis 
│   ├── 📁 pages          # páginas principais (Home, Favoritos, Detalhes)
│   ├── 📁 hooks          # hooks customizados 
│   ├── 📁 context        # contexto e useReducer para favoritos
│   ├── App.jsx
│   ├── main.jsx
│   └── styles.css
├── package.json
└── README.md
