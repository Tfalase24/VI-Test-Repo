# Vi test project

This is a repo for a test project, this project will show me what you can do, and how you handle a new tech stack, FE (Frontend), BE (Backend), and a new language.

For this project you will have a week max to complete the task, if you compete the tasks early then you can either stop the project or continue and see what else you can you add to it.

## !Important Notes!

Please work on the task in the order that you think is the most important, so if you don't complete all the tasks in a week then at least the most impoartant have been done.

## Task

We have been tasked by a client to build a proof of concept in a week. Our client would like a very basic web based POS (point of sales system).

### Requirements

- As a user I should be able to login
- As a user I should be able to sign up with a email and password (password should be saved as a hashed string)
- As a user I should be able to see all products that I can purchase
- As a user I should be able to add a new product →

```tsx
type Product = { price: number, description: string, stock: number, lastSoldAt: number(epoch time stamp)}
```

- As a user I should be able to add multiple products to the basket
- As a user I should be able to remove products from the basket
- As a user I should be to complete a purchase with the items in my basket

### Technology Requirements

- Backend

  - Typescript → [doc](https://www.typescriptlang.org/)
  - Apollo Server → [doc](https://www.apollographql.com/docs/apollo-server/)
  - Non relational local database e.g. **[lowdb](https://www.npmjs.com/package/lowdb)** which is currently in in the repo
  - use [Eslint](https://eslint.org/) and [Prettier](https://prettier.io/)

- Frontend
  - React Typescript
 
 

