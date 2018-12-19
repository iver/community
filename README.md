# Community

**Community**, is an example based on the tutorial published on  [https://www.howtographql.com/graphql-elixir/1-getting-started/](). As the tutorial said ...

> You’re going to build an app called *Community*, and you can think of it as a miniature version of Hacker News, Slashdot, or any other site that displays content on the basis of user submissions and votes.

## Getting Started

### 1) Install Dependencies

The First you’ll need to have [Elixir](https://elixir-lang.org/) and [Erlang](https://www.erlang.org/) installed on your machine. See [https://elixir-lang.org/install.html]()

### 2) Install this generator:

```
$ mix local.hex --force && \
$ mix local.rebar --force && \
$ mix archive.install https://github.com/phoenixframework/archives/raw/master/phx_new.ez
```

### 3) Update your dependencies:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Start Phoenix endpoint with `mix phx.server`

### 4) Testing with playground

Now you can visit [`localhost:4000/graphiql`](http://localhost:4000/graphiql) from your browser.

Ready to run in production? Please [check the deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
