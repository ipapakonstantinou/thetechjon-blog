# thetechjon-blog

Published posts for [thetechjon.com](https://thetechjon.com).

Each post is an `.mdx` file under `content/posts/` with frontmatter:

```yaml
---
title: "Post title"
slug: "post-slug"
date: "2026-05-25"
description: "One sentence shown in the index."
tags: ["tag-a", "tag-b"]
---
```

This repo holds only PUBLISHED posts. The site fetches them at build time and
renders them on `/posts`. A push to this repo redeploys thetechjon.com (via a
Vercel deploy hook fired by `.github/workflows/rebuild-site.yml`), so a new post
goes live a couple of minutes after it lands here.

Drafts under review do not live here. They stay private in the thetechjon repo
and are visible only on the gated `/preview`.
