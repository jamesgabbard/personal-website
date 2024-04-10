# Personal Website
Full site hosted at [www.mit.edu/~jgabbard](https://www.mit.edu/~jgabbard/). Built with [jekyllBear](https://knhash.in/jekyllBear).

#### To build locally
Check the `_config.yml` file, and comment/uncomment the correct `url` and`baseurl` settings. Then run
```
jekyll build
jekyll serve
```
Navigate to [http://localhost:4000/](http://localhost:4000/) in a browser to view the site. 
Be sure to reset the `_config.yml` file afterwards before deploying.

#### To deploy
The `deploy.sh` script will upload the contents of the site to Athena.