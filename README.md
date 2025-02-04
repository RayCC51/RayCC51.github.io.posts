# This repo contain blog posts

See all posts: [RayCC51](https://raycc51.github.io/)

## Use

[Repo File Sync Action](https://github.com/marketplace/actions/repo-file-sync-action) by [BetaHuhn](https://github.com/BetaHuhn)

## How it works

**RayCC51/RayCC51.github.io.posts/** has `.github/workflows/sync.yml`, `.github/sync.yml`

**RayCC51/RayCC51.github.io/** has `.github/workflows/sync-pull-request.yml`

When I _push_ posts inside `_posts`, this repositories

**Repo File Sync Action** automatically _push_ `RayCC51.github.io.posts/_posts/` to `RayCC51.github.io/_posts/`

`sync-pull-request.yml` automatically _merge_ _pull_ request from myself
