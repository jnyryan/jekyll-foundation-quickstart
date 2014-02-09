jekyll-foundation-quickstart
============================

a quick setup for a jekyll based blog using the foundation framework by zurb

This is just a quickstart to get someone up and running with a basic blog that provides the usual features:

- Blog Entries
- Categories
- Tags
- Pages

###Run the site
```
gem install jekyll
jekyll serve
```
###Change the site

in the _layouts folder just change the default.html
probably want to change the css as well.

###Deploy it on heroku

```
gem install bundler
gem install heroku
gem bundle install

heroku create --stack cedar
git push heroku master
heroku open

```

LICENCE: [MIT](LICENSE)


