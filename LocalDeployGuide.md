# Local Deploy Guide

## Environment

- Deno >= v1.9.2
- GitHub API v4

## Prepare

1. Generate a [GitHub Token](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token).
2. Create new file `.env` to project root directory.
3. Add an environmental variable `GITHUB_TOKEN` with the value of the GitHub Token you generated.

```
GITHUB_TOKEN=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

4. Run local server.

```
deno run --allow-net --allow-read --allow-env debug.ts
```

5. Open localhost from your browser.

http://localhost:8080/?username=lucthienphong1120

