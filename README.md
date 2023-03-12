# Github Action Release

GitHub Action that creates a new release.

```yaml

  - name: Create a Release
    id: create-release
    uses: clockwork-marketing-uk/actions-release@1.0.0
    with:
        github-token: ${{ secrets.GITHUB_TOKEN }}

```

To create a Pre Release add the following

```yaml

    with:
        pre

```
