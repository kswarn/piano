# πano

A single static page (`index.html`). No build step, no dependencies.

## Deploy with the Vercel CLI
```
npm i -g vercel
cd piano-vercel
vercel          # first run: answer the prompts, accept the defaults
vercel --prod   # publish to production
```

## Deploy from GitHub
1. Put this folder in a GitHub repo.
2. On vercel.com choose Add New > Project, then import the repo.
3. Framework Preset: Other. Leave Build Command and Output Directory empty. Click Deploy.
