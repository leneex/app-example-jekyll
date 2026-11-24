# Jekyll

Example [Jekyll](https://jekyllrb.com/) static site. Jekyll is a Ruby static site generator that turns Markdown and Liquid templates into a website.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/_site` |
| Install command | leave empty |
| Build command | `bundle exec jekyll build` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
bundle install

# run in development mode
bundle exec jekyll serve

# build for production
bundle exec jekyll build
```

Requires the Ruby version specified in `.ruby-version` and Bundler.
