# The Bootleg Hacker theme

welcome to regulad's hacker fork, its ok ig

## Use

If you want to use this pile o' turd yourself, set the `remote_theme:` field in your Jekyll `_config.yml` to `regulad/hacker`. 

If you aren't using Github Pages, you should add `gem "github-pages"` to your Gemfile under the `jekyll_plugins` bundler group.

Example:

```gemfile
group :jekyll_plugins do
  gem "github-pages"
end
```

You also need to add it to your `_config.yml` under `plugins`.

Example:

```yaml
plugins:
  - github-pages
```


## Elements

* `show_downloads: truthy/falsey`
* `show_description: truthy/falsey`
* `google_analytics: id`
* `post_show_tags: truthy/falsey`
* `post_show_author: truthy/falsey`