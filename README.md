# requiem
**Export Ghost blog JSON dumps to Jekyll.**

This was created as a way to backup and replicate my Ghost-based blog on Github, however it can easily be used to migrate your Ghost blog entirely to Jekyll.

## installation:

`sudo npm install -g requiem/`

## usage:

`requiem json_dump_path output_path`

`json_dump_path` is the path of the file obtained at *YOURBLOG.COM/ghost/settings/labs* -> **export**.

## example:

static files are output to `/_posts` here: https://github.com/david-cako/cako.io/tree/gh-pages

And the final page is visible at: https://david-cako.github.io/cako.io/


