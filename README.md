# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args:
['--no-sandbox'] }` in your call to `puppeteer.launch`

__This fork of the [jontewks buildpack](https://elements.heroku.com/buildpacks/jontewks/puppeteer-heroku-buildpack)
adds support [emojione](https://github.com/emojione/emojione/tree/master/extras/fonts) 
