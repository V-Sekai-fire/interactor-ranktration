# interactor-ranktration

An Elixir library that ranks algorithms, models or approaches by weighted scores across several criteria.

## What it is for

It compares candidates pair by pair on weighted metrics, turns the comparisons into a tournament ranking, and measures how stable that ranking is. The module documentation carries the API, with its examples run as doctests. The method derives from a published relative-ranking approach for agent trajectories: <https://art.openpipe.ai/fundamentals/ruler>.

## Build and test

    mix deps.get
    mix test

## Licence

MIT. See [LICENSE](LICENSE).
