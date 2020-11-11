# [Template Working Now 🐘](https://koumaza.github.io/smui-sapper-rollup-template)
# How to use
## For GitHub-Pages (GitLab-Pages)
### 1. Replace to your information
#### `src/server.js`
```javascript:server.js
...

.use
  process.env.BASE_NAME || '/smui-sapper-rollup-template',
  
...
```

| Before | After |
|---|---|
|  `process.env.BASE_NAME \|\| '/smui-sapper-rollup-template',` |  `process.env.BASE_NAME \|\| ` ___`'/YourRepositoryName'`___ `,` |
### 2. Enable Dependabot
# Refer to
- https://github.com/kafai97/sapper-smui-boilerplate
- https://github.com/hperrin/svelte-material-ui/issues/361
