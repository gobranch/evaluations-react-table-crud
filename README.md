# React Table CRUD evaluation

- The starting point code in this repo queries a list of all users and puts them on the screen as JSON.

- The schema you have to work with is in the repo as `schema.graphql`.

- You'll have to create an `env.js` file in the `src` directory with the content:

```js
export default {
  GRAPHQL_ENDPOINT: '',
  GRAPHQL_API_KEY: ''
};
```

- Fill in the endpoint and API key you received in the `env.js` file.

- You should have also received a link to Zeplin containing the design you have to implement.

- If you haven't received either of those things, reach out to us and we'll get you set up right away.

- There's a `resetUsers` mutation that you can use at any time to restore the original user data set.

- The sample code in the repo uses React hooks to interact with the GraphQL API, but if you aren't comfortable with hooks yet then feel free to use whatever other method you'd like.

- You'll have to implement the two screens in the Zeplin design as separate routes, using client side routing.
