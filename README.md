# blog

## Install hugo
```bash
brew install hugo
hugo version
```

## Clone
```bash
git clone https://github.com/srcio/blog.git
cd blog
```

## New post
```bash
hugo new -k posts content/posts/my-first-post.md
```

## New series
```bash
hugo new -k series content/series/my-first-series.md
```

## Run
```bash
hugo server -D
```

## Build
```bash
hugo -D
```