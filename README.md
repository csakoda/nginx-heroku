# nginx-heroku


[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/csakoda/nginx-heroku)

## Manual Deploy Steps 
If the button isn't working...
```
heroku create --buildpack=https://github.com/csakoda/nginx-buildpack
git push heroku master
heroku open
```

## TODO
(optional) Replace the nginx.conf.erb
