# How to Build

Run two commands--one to build locally, and another to push static files to a branch on repo which Cloudflare picks up and serves.

```shell
hugo --gc --minify --baseURL "https://photo.visruth.com/"
npx gh-pages -d public -b deploy -m "Deploy site update via local build"
```
