# Identicon

<p align="center">
  <a href="https://github.com/chakrakan/identicon"><img src="https://github.com/chakrakan/identicon/blob/main/docs/chakrakan.png" width="350" alt="Chakrakan identicon" /></a>
  <p align="center">Identicon for <a href="https://github.com/chakrakan">chakrakan</a></p>
</p>

Generate identicons similar to Github's default identicon style (250px by 250px grid with 50px tall squares making pattens) based on a string input.

### Underlying Process

- String input
- Compute MD5 hash
- List of nums based on string
- Pick color
- Build grid
- Convert grid into image
- Save image file

### Running locally

- `mix deps.get`
- `iex -S mix`
- `iex> Identicon.main("YOUR INPUT")`

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
