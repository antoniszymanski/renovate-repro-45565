## Reproduction steps:

1. Clone this repository.
2. Wait for the first PR to be created.
3. Merge the first PR using the "Rebase and Merge" strategy. Do not delete the "renovate/lock-file-maintenance" branch.
4. Wait until the second PR is created.

## Current behavior

After [the first PR](https://github.com/antoniszymanski/renovate-repro-45565/pull/1) is merged, [an identical PR](https://github.com/antoniszymanski/renovate-repro-45565/pull/3) **is** created.

## Expected behavior

After [the first PR](https://github.com/antoniszymanski/renovate-repro-45565/pull/1) is merged, [an identical PR](https://github.com/antoniszymanski/renovate-repro-45565/pull/3) **isn't** created.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/45565
