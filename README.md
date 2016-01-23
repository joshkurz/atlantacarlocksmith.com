# Open Sesame website files

Open Sesame is an Atlanta locksmith, who believes in open source. 
Open Source and Open Sesame go together well. This is why we have open sourced our site and are releasing it to the world. This site runs on a Jekyll back end to build the site. 
The site is hosted in s3 with AWS Cloudfront as the caching layer. This allows the site to be up 99.9% of the time, with super fast results for our customers.

## Atlanta Locksmith

If you are interested in learning more about Open Sesame, go and see the [atlanta locksmith](http://atlantacarlocksmith.com) site.

## Documentation

* install nodejs (we prefer using https://github.com/creationix/nvm)
* install [Jekyll](http://jekyllrb.com)
* npm install -g grunt-cli

### Running the site locally

1. grunt watch
2. open a new terminal
3. jekyll serve --watch
4. navigate to localhost:4000
