# Teacher

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Install Node.js dependencies with `npm install` inside the `assets` directory
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

---

# Notes

## Getting Started with Phoenix

`mix phx.new teacher`

Update database dev configuration in `config/dev.exs`

`mix ecto.create`

`mix phx.server`

`mix phx.gen.html Blog Post posts title:string body:text`

The generator creates all sorts of things, including:

- Controller
- View
- Templates
- Migration
- Modules

`mix ecto.migrate`

`mix phx.routes`