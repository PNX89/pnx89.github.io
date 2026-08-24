# pnx89.github.io

The map that sits at [pnx89.github.io](https://pnx89.github.io): what each repository in this
toolset compares against what, grouped by what it argues, with a technology view read out of
each repository's own `pyproject.toml`.

`index.html` is generated, not hand written, from the same manifest that writes every card at
`pnx89.github.io/<REPO>`. Editing it here would be overwritten on the next run; the manifest is
the place to change anything.

Deployment builds nothing. It checks the page is not empty, carries no banned dash, and has no
link that fails to return 200, then uploads it. A map with a dead link on it is worse than no
map, because it is the page a CV points at.
