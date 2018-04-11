## GraphQL Workshop

Download dependencies with `yarn` or `npm install`.

Create a personal access token on GitHub [https://github.com/settings/tokens](https://github.com/settings/tokens).

Export your token as `REACT_APP_GITHUB_TOKEN` and run `yarn start`

```
REACT_APP_GITHUB_TOKEN=abcd123 yarn start
```

Your browser should automatically open to localhost:3000 and you'll see a page with the heading "GraphQL Playground".

Next up: [Create your first query](https://github.com/dwwoelfel/graphql-workshop/tree/first-query)

To create this repo from scratch, you'd do:

```
create-react-app graphql-workshop
cd graphql-workshop
yarn add apollo-boost graphql react-apollo@beta
```
