# pizza.shop

![Preview do projeto - Página Sign in](/.github/preview-sign-in.png)
![Preview do projeto - Página Home](/.github/preview-home.png)
![Preview do projeto - Página Pedidos](/.github/preview-pedidos.png)

<br>

## 💻 Projeto

**[pizza.shop](https://github.com/AdrianoTobias/pizzashop)**, é uma aplicação voltada à gestão de _Food Delivery_, a qual disponibiliza um dashboard com diversas métricas em relação a pedidos, receita e produtos populares, além de uma área dedicada aos pedidos, onde pode-se realizar integrações como a mudança de status, visualização de detalhes e aplicação de filtros, possibilitando acompanhar cada pedido, desde o seu recebimento, até a sua entrega.

O projeto envolve página de login, atualização de perfil, criação de novo login, logout e definição de tema ("Ligh", "Dark" ou "System").

Há, ainda, diversos casos de teste de ponta a ponta (E2E).

É uma aplicação desenvolvida durante o **[MBA Fullstack](https://www.rocketseat.com.br/mba)**, provido pela **[Rocketseat](https://rocketseat.com.br/)**, em parceria com a **[Sirius Education](https://landing.sirius.education/home/)**.


## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [ReactJS](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Shadcn/ui](https://ui.shadcn.com/docs/components/accordion)
- [Tailwindcss](https://tailwindcss.com/)
- [Recharts](https://recharts.org/en-US/)
- [Sonner](https://sonner.emilkowal.ski/)
- [React Query](https://tanstack.com/query/latest)
- [Axios](https://axios-http.com/ptbr/docs/intro)
- [Zod](https://github.com/colinhacks/zod)
- [Vitest](https://vitest.dev/)
- [Happy DOM](https://github.com/capricorn86/happy-dom)
- [Testing Library](https://testing-library.com/)
- [Mock Service Worker](https://mswjs.io/)
- [Playwright](https://playwright.dev/)


## 🚀 Como executar

Clonar o projeto e acessar a pasta do mesmo:

```bash
$ git clone https://github.com/AdrianoTobias/pizzashop.git
$ cd pizzashop
```

Para iniciá-lo:
```bash
# Instalar as dependências
$ npm install

# Iniciar a aplicação
$ npm run dev
```
A aplicação estará disponível no browser, pelo endereço http://localhost:5173.

Para executar os testes via Vitest:
```bash
# Executar os testes
$ npm run test
```

Para executar os testes via Mock Service Worker (MSW):
```bash
# Iniciar a aplicação
$ npm run dev:test
```
A aplicação estará disponível no browser, pelo endereço http://localhost:50789.

Para executar os testes via Playwright:
```bash
# Executar os testes
$ npx playwright test

ou

# Abrir interface
$ npx playwright test --ui
```


As API's consumidas por esse projeto são providas por um servidor externo, o qual precisa ser baixado e executado, conforme sua respectiva [documentação](https://github.com/rocketseat-education/pizzashop-api).



[Adriano Tobias](https://github.com/AdrianoTobias)