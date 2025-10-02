# Installing `@openai/codex`

The command `npm i -g @openai/codex` currently fails in this environment because the registry request returns `403 Forbidden`.

```
npm i -g @openai/codex
npm error code E403
npm error 403 Forbidden - GET https://registry.npmjs.org/@openai%2fcodex
```

If you have network access to the required registry, rerun the command outside of this sandbox or mirror the package to an accessible registry.
