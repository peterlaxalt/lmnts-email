# L&M Email Templates
By Peter Laxalt 2018

[www.laxaltandmciver.co](http://www.laxaltandmciver.co/)

Simple structure for building email templates with Sass.

## Setup
1. Install Sass using [their guide.](http://sass-lang.com/install)
2. Watch the `/sass/` directory and compile into css via Terminal using `sass --sourcemap=none --watch sass:stylesheets`
3. Unix: Boot up a SimpleHTTPServer with Python to serve your files with ```python -m SimpleHTTPServer 1337```
4. Navigate to [localhost:1337](localhost:1337) to test your templates.

## Test On Device
- You can access your ```localhost:1337``` from any device because ```.ngrok``` is amazing.
- In terminal, simply type ```$ ./ngrok http 1337``` to fire up a server and they will provide urls.
