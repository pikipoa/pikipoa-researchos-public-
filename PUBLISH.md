# Publish target

Intended GitHub repository:

`pikipoa/researchos-public`

This working repository is ready to push once that public repository exists and is accessible to the connected GitHub account.

Recommended push:

```bash
git remote add origin https://github.com/pikipoa/researchos-public.git
git push -u origin main --follow-tags
```

After push, articles should link to the exact commit permalink or the `question-002-v1-public-genesis` tag, not only to `main`.
