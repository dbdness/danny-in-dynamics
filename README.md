# Danny in Dynamics
Repo for the blogging project "Danny in Dynamics".

Built with [Hugo](https://gohugo.io/), bootstrapped with [Poison](https://github.com/lukeorth/poison).

## Cloning Instructions
Clone with the `--recurse-submodules` flag to retrieve the main theme (**NB**: Build will not work on Windows until [PR #181](https://github.com/lukeorth/poison/pull/181) is merged).

```bash
$ git clone https://github.com/dbdness/danny-in-dynamics.git --recurse-submodules
```

## Creating New Content
Use Hugos built-in static file generation command to ensure correct theme compliance:

```bash
$ hugo new content posts/dynamics-power-platform/introducing-developer-tooling/index.md
```

## Run Development Server
Run the development server locally with the `-D` flag to include drafts.
```bash
$ hugo serve -D
```