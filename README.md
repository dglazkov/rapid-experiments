# Rapid Experiments Repo Template

A repo for experiments and tinkering with stuff. It is loosely based on the findings documented in [this blog post](https://glazkov.com/2023/06/05/development-environment-for-rapid-experimentation/).

To use it as the template for your own project:

:one: In a directory where you want to create your project.

```bash
npx degit dglazkov/rapid-experiments
```

:two: Replace various placeholders (each uses the `{{handlebar}}` syntax) throughout the repository:

- `npm_org_name` -- the npm organization name that will house all the packages published out of this monorepo.

- `team_name` -- the name of your team that will do the rapid experimenting.

- `repo_url` -- the url of your repository.

- `repo_description` -- the description of your repository.

:three: Replace this README with your own.
