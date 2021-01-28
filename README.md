# The Bootleg Hacker theme

Welcome! This is a better version of the Jekyll theme pages-themes/hacker, and it is also compatable with Github Pages.

## Notice!

I am now developing my own theme: [`regulad/crust-tastic`](https://github.com/regulad/crust-tastic). It shares some similarities, but is more detached from [`pages-themes/hacker`](https://github.com/pages-themes/hacker).

## Elements

Over pages-themes/hacker, I have made things a lot more configurable.

* `show_header: truthy/falsey` Controls the footer at the bottom of the page. This will have basic navigation. See [my website](https://regulad.xyz/) for a full example.
  * `show_description: truthy/falsey` Controls the description underneath the title.
  * `show_downloads: truthy/falsey` Controls the download buttons and "View on Github" buttons.
* `show_footer: truthy/falsey` Controls the footer at the bottom of the page. This will have basic navigation. See [my website](https://regulad.xyz/) for a full example.

* `post_show_tags: truthy/falsey` Controls showing the tags at the bottom of a post.
* `post_show_author: truthy/falsey` Controls showing the author at the top of a post.

* `color: light/dark` Controls the color pallete of the webpage. Default is dark.
* `favicon: truthy/falsey` Controls the favicon of the webpage. If you would like to use a custom path, subsitute `truthy/falsey` with `/path/to/favicon`, otherwise it will use the root of the site.


## Use

If you want to use this pile o' turd yourself, set the `remote_theme:` field in your Jekyll `_config.yml` to `regulad/hacker`. 

```yaml
remote_theme: regulad/hacker
```

If you aren't using Github Pages, you should add `gem "github-pages"` to your Gemfile under the `jekyll_plugins` bundler group.

```ruby
source 'https://rubygems.org'
group :jekyll_plugins do
  gem "github-pages"
end
```

You also need to add it to your `_config.yml` under `plugins`.

```yaml
plugins:
  - github-pages
```
