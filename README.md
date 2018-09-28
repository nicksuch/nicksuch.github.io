# nicksuch.github.io
Nick's test page for Bootcamp

- [GitHub](https://github.com/nicksuch/)
- [StackOverflow](https://stackoverflow.com/users/663607/nicksuch)
- [LinkedIn](https://linkedin.com/in/nicksuch)

## Setting up Jekyll and GitHub Pages for blogging

1. Visit https://jekyllrb.com/

 - `gem install ...` doesn't work?
 - Do you have Homebrew? If not, [install Homebrew](https://brew.sh/).
 - [Install rbenv using Homebrew](https://github.com/rbenv/rbenv#homebrew-on-macos)
 - Does `jekyll serve` work?

2. Jekyll ingredients

 - Ruby (while you will need Ruby installed to run Jekyll on your machine, you won't actually write any Ruby code)
 - [YAML](http://yaml.org/) (data format for Front Matter, Config)
 - [Liquid](https://jekyllrb.com/docs/liquid/) (for templating)
 - [Markdown](https://commonmark.org/help/) (for writing content, compiles to HTML)
 - [Sass](https://jekyllrb.com/docs/assets/) (for styling, compiles to CSS)

3. Adding a blog to your static site with Jekyll

  - `Gemfile` (use [`github-pages`](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/))
  - `_config.yml`
  - Front Matter (with YAML)
  - `_layouts`
  - `_includes`
  - `_posts` (this is a `collection`)
  - `blog.html` (list your blogs here with a Liquid for loop)

4. Deploy with GitHub Pages

 - If you've previously deployed your site to _username.github.io_, you can just `git push` your changes, and GitHub's servers will run `jekyll build` for you each time
