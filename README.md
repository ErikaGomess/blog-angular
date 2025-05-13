# 📝 Blog Angular

Este é um projeto de blog desenvolvido com **Angular 16+ no formato standalone**, utilizando rotas, componentes reutilizáveis, consumo de API externa e boas práticas de organização.

## 📌 Funcionalidades

- ✅ Listagem de posts com visual moderno
- ✅ Navegação com Angular Router
- ✅ Página de detalhe de cada post
- ✅ Estilo com SCSS e Bootstrap
- ✅ Footer com redes sociais e ano atual
- ✅ Projeto com estrutura modular e limpa

## 🚀 Tecnologias Utilizadas

- Angular 16+ (standalone components)
- Angular Router
- Bootstrap 5
- SCSS
- API pública JSONPlaceholder (https://jsonplaceholder.typicode.com/posts)

## 🧱 Estrutura do Projeto

```
blog-angular/
├── src/
│   ├── app/
│   │   ├── pages/
│   │   │   ├── post-list/
│   │   │   └── post-detail/
│   │   ├── components/
│   │   │   ├── post-card/
│   │   │   └── footer/
│   │   ├── services/
│   │   │   └── post.service.ts
│   │   └── app.config.ts
│   ├── main.ts
│   └── index.html
```

## 🔧 Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/blog-angular.git
   cd blog-angular
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   ng serve
   ```

4. **Acesse no navegador:**
   ```
   http://localhost:4200
   ```

## ✨ Melhorias Futuras

- Autenticação de usuários
- Comentários nos posts
- Criar, editar e excluir posts (CRUD)
- Responsividade mobile aprimorada

## 👩‍💻 Desenvolvido por

Erika de Jesus Gomes  
🔗 [LinkedIn](https://www.linkedin.com/) | ✉️ erikadev@email.com
