hubot-info
==========

A simple server endpoint for getting info about Hubot.

### Installation

```bash
$ npm install --save hubot-info
$ vim external-scripts.json # add "hubot-stenographer" to the array
```

### Usage

Once the script is enabled for your bot, you're good to go!

### Credit

This script is a piece of what is shipped with the normal Hubot distribution.
I didn't want to have a `scripts/` directory so I decided to strip out everything
but that which was absolutely essential to my end (a useful ping endpoint, basically)
and distribute it as an NPM module.

Tom Bell (@tombell)
GitHub, Inc.
Parker Moore (@parkr)
