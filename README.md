# Nx Monorepo
Example of Nx Monorepo

## Install Nx globally
```
npm i -g nx
```

## Initialize Monorepo
```
npx create-nx-workspace@latest my-monorepo --preset=react-monorepo
```

This will create all the scaffolding code for the Nx Monorepo
```
[ NX ]   Let's create a new workspace [https://nx.dev/getting-started/intro]

✔ Application name · my-react-app
✔ Which bundler would you like to use? · vite
✔ Test runner to use for end to end (E2E) tests · playwright
✔ Default stylesheet format · scss
✔ Which CI provider would you like to use? · github

 [ NX ]  Creating your v20.4.5 workspace.
```

## Lint React App
```
cd my-monorepo
nx lint my-react-app
```

## Test React App
```
cd my-monorepo
nx test my-react-app
```

## Build React App
```
cd my-monorepo
nx build my-react-app
```

## Run React App
```
cd my-monorepo
nx serve my-react-app
```
