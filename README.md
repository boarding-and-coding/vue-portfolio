# vue-portfolio

## Project setup

```bash
npm install
```

### Compiles and hot-reloads for development

```bash
npm run serve
```

### Compiles and minifies for production

```bash
npm run build
```

### Lints and fixes files

```bash
npm run lint
```

### Deploy to GCS for hosting

1. Create a service account with Storage Object Admin Role
2. Give it a key
3. In Github Secrets add the secrets in the .github/workflows/deploy.yml file
4. Make the bucket viewable for allUsers
5. Setup DNS to point your domain at your GCS Bucket

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
