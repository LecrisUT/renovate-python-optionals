# 37474

## Current behavior

There is no simple way of filtering the PEP621 `project.optional-dependencies` or
`dependency-groups` by the name of the optional/dependency group.

## Expected behavior

Have either individual addressable dep-types, similar to `tool.hatch.envs.<env-name>`
or have any other matchers that could be used. In the current example, there should
be 3 different PRs created for each group.

## Link to the Renovate issue or Discussion

See [renovatebot/renovate#37474](https://github.com/renovatebot/renovate/discussions/37474).
