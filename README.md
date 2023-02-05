# Get Started with Julia

A gentle introduction to Julia with simple data science related examples.

## Tips on Starting a New Julia Project

_Reference: [Julia Workshop - 1: Getting started with Julia](https://crsl4.github.io/julia-workshop/session1-get-started.html#creating-a-new-project-environment)_

1. Navigate to your project folder in the terminal
2. activate the julia console by type `julia`
3. type `]` to change to `pkg > `
4. type `activate .` creates `Project.toml, Manifest.toml` files. These files should not be updated by hand.
5. add packages as required using `add <package-name>`

## Working on existing project

Follow step 1 to 3 above after cloning the repo.

then type the following:

```
(your-project) pkg> instantiate
(your-project) pkg> update
```
