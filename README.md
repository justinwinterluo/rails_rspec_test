# rails_rspec_test

A small Rails practice app for getting back into programming, one commit at a time.

> **To future me:** You stepped away for a while, and that's okay. You haven't
> lost the skills; they're just waiting to be dusted off. Every developer
> feels rusty after a break. What matters is opening the editor and writing a
> line of code today. Small steps add up. Keep going. 🚀

## What it does right now

| URL | What you'll see |
|---|---|
| `/say/hello` | A greeting with the current time and a link to Goodbye |
| `/say/goodbye` | A farewell message and a link back to Hello |

## Tech stack

- Ruby 3.1.2
- Rails 7.0
- SQLite
- RSpec for tests

## Getting started

```sh
bundle install
bin/rails db:prepare
bin/rails server
```

Then open <http://localhost:3000/say/hello>.

## Running the tests

```sh
bundle exec rspec
```

## Next steps (my learning roadmap)

- [ ] Add a `Sandwich` class so `spec/sandwich_spec.rb` passes
- [ ] Write request specs for `/say/hello` and `/say/goodbye`
- [ ] Clean up duplicate routes in `config/routes.rb`
- [ ] Upgrade `rspec-rails` and swap `factory_girl_rails` for `factory_bot_rails`
- [ ] Build my first model with validations and tests
- [ ] Deploy the app so it's live online

Every box I check here is progress. Progress, not perfection.
