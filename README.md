# Blog-em Ipsum

Project is a simple Blog Post application using placeholder text (like [Lorem ipsum](https://en.wikipedia.org/wiki/Lorem_ipsum)) and relates to [React Query / TanStack Query: React Server State Management](https://www.udemy.com/course/learn-react-query) Udemy course by [Bonnie Schulkin](https://www.udemy.com/user/bonnie-schulkin).

**Server**

The server is [{JSON} Placeholder](https://jsonplaceholder.typicode.com/) fake API. In particular endpoints which simulate a blog server.

Front-end can get posts, get comments on the posts and so forth. Front-end also makes updates, but the updates don't actually make any changes to the data on the server. The server gives a response as though there were changes, but the server data remains the same.

**Front-end**

Front-end is focused on practicing next [TanStack Query](https://tanstack.com/query/latest) aspects:

- Fetching data
- Working with loading / error states (informing user when we're loading data & when there's been an error)
- React Query dev tools (getting insights on what's going on with the queries)
- Pagination
- Prefetching (prefetch next page so that it's seamless when the user clicks on the next page and that data has been gotten right away)
- Mutations (making changes to the data on the server)

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### Running the Project

Project uses NPM as package manager. Run `npm install` to install project dependencies and then `npm run dev` to start development.

### Deploy

Project is deployed to GitHub Pages: https://ntonbala.github.io/blog-em-ipsum. Deployment is done automatically from `main` branch.
