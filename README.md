# Nyhavn in pure CSS (well OK, SASS!)

## Install SASS

    npm i -g sass

## Watch SCSS directory and compile to CSS

    sass --watch scss:css

## If you want minimised CSS

    sass --watch scss:css --style compressed

## Start a local webserver

    python -m SimpleHTTPServer

Open web browser to http://localhost:8000/

## Auto refresh

Add the following snippet in the `<head>` of index.html

    <script type="text/javascript" src="https://livejs.com/live.js"></script>

It will auto refresh with changes.
