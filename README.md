# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args:
['--no-sandbox'] }` in your call to `puppeteer.launch`

__This fork is of the (GautierT/puppeteer-heroku-buildpack) buildpack
adds support for heroku-18-stack. Basically allows the build with heroku-18-stack and installs the same dependencies as for heroku-16-stack
