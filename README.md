# greet

A small example cog for [Quarz](https://quarz.dev): a class, a
compile-time macro (`static def`) and a test. It is what the Quarz guide's
cogs page depends on, and the Quarz repository's weekly check fetches it.

```toml
# Cog.toml of an application
[dependencies]
Greet = { git = "https://github.com/quarz-lang/greet", tag = "v1.0.0" }
```

```ruby
puts Greet::Greeter.new("Quarz").hello   # => Hello, Quarz!
```

`quarz test` runs its tests. Licensed under MIT No Attribution (LICENSE).
