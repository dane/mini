# mini 

Version: 0.0.1
Demo: [daneharrigan.com](https://daneharrigan.com)

A minimal Hugo blog theme that is responsive with a touch of purple. 

## Overview

This theme is _heavily_ inspired by [hmarr.com](https://hmarr.com). I would have
happily used his theme, but it hasn't been open sourced so I put together
something similar. I appreciate how clean and simply content is presented and
that dynamic farewell in the footer are a nice touch.

To stay in line with inspiration and not a blatant copy, nothing was taken from
Harry's site. I wrote everything myself and opted to skip the dynamic footer. I
use the [Hack](https://sourcefoundry.org/hack/) font instead of
[JetBrains Mono](https://www.jetbrains.com/lp/mono/) and I am partial to purple.

## Syntax highlighting

I have strong opinions on syntax highlighting. This theme was created with
highlighting disabled. I believe and have seen first hand, without syntax
highlighting, code must be clean and simple. You don't really have a choice.
I'll write about this one day.

## Configuration

Mini only looks for three keys in `hugo.yaml`'s `params`.

- `github` - A link to your GitHub page.
- `mastodon` - A link to your Mastodon profile.
- `footer` - Free form text that will appear in the footer of every blog post.

For example:

```yaml
params:
  github: 'https://github.com/dane'
  mastodon: 'https://mastodon.social/@daneharrigan'
  footer: |-
    Thank you for reading an entry in my collection of blog posts.
```

## Contributing

I'm happy to discuss new features and receive pull requests. Mini doesn't
support Twitter, Instagram, Gitlab, etc. only because I don't use them, but it
could with your help.
