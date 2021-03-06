#jekyll-foundation-quickstart


a quick setup for a jekyll based blog using the foundation framework by zurb

This is just a quickstart to get someone up and running with a basic blog that provides the usual features:

- Blog Entries
- Categories
- Tags
- Pages
- Post Comments using ***DISQUS***
- Contact form using ***SimpleForm***
- Google Analytics
- Heroku Deployment

See it running in this [demo](http://jekyllfoundationquickstart.herokuapp.com/)

###Change the site

Obviously you'll want to customise this for yourself so the best place to start is in the _layouts folder just change the ***default.html***.
Probably want to change the styles in the ***css*** folder as well.

###Run the site locally

Jekyll is Ruby based, so you'll need to have Ruby installed before running it.

With Ruby installed, install the Jekyll gem and run it using these commands.


```
gem install jekyll
jekyll serve
```

###Deploy the site on heroku cloud

Heroku is a cloud platform as a service supporting several programming languages. 
You can easily deploy the site to Heroku for free using the commands below.

```
gem install bundler
gem install heroku
gem bundle install

heroku create --stack cedar
git push heroku master
heroku open

```

LICENCE: [MIT](LICENSE)


