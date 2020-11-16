# [Template Working Now 🐘](https://koumaza.github.io/smui-sapper-rollup-template)
# [smui](https://github.com/hperrin/svelte-material)-[sapper](https://github.com/sveltejs/sapper)-[rollup](https://github.com/rollup/rollup)-template
# How to use
## For GitHub-Pages (GitLab-Pages)
### 0. Create Repository From This
#### 0-A. Open https://github.com/koumaza/smui-sapper-rollup-template/generate
#### 0-B. Enter your like repo name in `Repository Name *`
#### 0-C. Enable `Include all branches` checkbox
#### 0-Z. Create Repository
>### 0.1. Alternative method (not recommend)
>#### 0.1-A. Open https://github.com/new/import
>#### 0.1-B. Enter `https://github.com/koumaza/smui-sapper-rollup-template` in "Your old repository’s clone URL"
>#### 0.1-C. Enter your like repo name in `Repository Name *`
>#### 0.1-Z. Create Repository
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
#### `package.json`
Replace to your identify!
### 2. Enable Dependabot
### 3. Repository Configuration
#### 3-A. Check default branch
If already set other than `master`, set to `master`
#### 3-B. GitHub-Pages (GitLab-Pages)
Enable feature
> (Or, deploy to GitLab-Pages)
### 4. Rewrite `README.md`
Rewrite for your thing, and enjoy!
# Refer to
- https://github.com/kafai97/sapper-smui-boilerplate
- https://github.com/hperrin/svelte-material-ui/issues/361
