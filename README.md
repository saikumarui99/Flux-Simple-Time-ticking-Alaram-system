# Flux-Simple-Time-ticking-Alaram-system
Based on the architecture suggestions from Facebook, this alaram  will help you set time automatically. It has included the flux-react extension to React JS, flux-react.

Read more about FLUX over at Facebook Flux and I wrote a post about it too: My experiences building a FLUX application and React JS and FLUX

Development

Run npm install
Run gulp
Start a webservice in the build folder, f.ex. python -m SimpleHTTPServer
Go to localhost:8000 to display the app
Go to localhost:8000/testrunner.html to see your tests
Any changes to app or styles folder will automatically rebuild to build folder
Both tests and application changes will refresh automatically in the browser
Run gulp test to run all tests with phantomJS and produce XML reports
Minify the code, ready for production

Run gulp deploy
Directory

build/: Where your automatically builds to. This is where you launch your app in development
dist/: Where the deployed code exists, ready for production
styles/: Where you put your css files
specs/: Where you put your test files
gulpfile: Gulp configuration
