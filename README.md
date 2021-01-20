# Listen Headlines Podcast sites

[Podcast site](https://ilanh.github.io/podcats/)

### Install

1. Clone the repo: `git clone git@github.com:ilanh/podcats.git`
2. Install [Jekyll](https://jekyllrb.com/docs/installation/): `gem install jekyll`, check [#1](https://github.com/Sylhare/Type-on-Strap/issues/1) if you have a problem.
3. Install the theme's dependencies: `bundle install`
4. Run the Jekyll server: `bundle exec jekyll serve`

## Structure

Here are the main files of the template

```bash
Type-on-Strap
├── _includes	               # theme includes
├── _layouts                   # theme layouts (see below for details)
├── _portfolio	               # collection of article to be populated in the portfolio page
├── _posts                     # Blog posts
├── _sass                      # Sass partials 
├── assets
|  ├── js	               # theme javascript, Katex, jquery, bootstrap, jekyll search, 
|  ├── css                     # isolated Bootstrap, font-awesome, katex and main css
|  ├── fonts		       # Font-Awesome, and other fonts
|  └── img		       # Images used for the template
├── pages
|   ├── 404.md		       # To be displayed when url is wrong
|   ├── about.md               # About example page
|   ├── gallery.md             # Gallery page for your photos
|   ├── portfolio.md	       # Portfolio page for your projects
|   ├── search.html	       # Search page
|   └── tags.md                # The tag page
├── _config.yml                # sample configuration
├── _data.yml
|  ├── authors.yml             # Update the post authors configurations 
|  ├── language.yml            # Localization configuration
|  └── social.yml              # Social configurations (RSS, Twitter, ...)
└── index.html                 # sample home page (blog page paginated)
```
