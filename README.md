# biggie
This is a fork for [kevinbeaty](https://github.com/kevinbeaty/biggie) with additions inspired by [killercup](https://github.com/killercup/biggie).

![](mascot.jpg)

biggie is the last mile of [big](https://github.com/tmcw/big). It turns
[Markdown](http://daringfireball.net/projects/markdown/) into slides,
and slides into a website, and even posts it online for you with the magic of
[bl.ocks.org](http://bl.ocks.org/) and [Gist](http://gist.github.com).

## cli

You can use biggie basically from the command line as an npm module:

```
npm install -g biggie
echo "# hi" | biggie > index.html
```

Pipe it into [browser](https://gist.github.com/defunkt/318247) or [bcat](http://rtomayko.github.io/bcat/)
to just view it in a browser immediately.

## develop

    git@github.com:tmcw/biggie.git

Then dependencies

    npm install

To start a server, run

    npm start

To bake `js/site.js` for static serving, run

    npm run-script make

## See Also

* [killercup's fork](http://killercup.github.io/biggie/) ([src](https://github.com/killercup/biggie)) adds localStorage backup,
  code highlighting, and style tweaks.

## Differences in this fork inspired by @killercup

- Add code highlighting using [highlight.js](http://softwaremaniacs.org/soft/highlight/en/) and extend *original* stylesheet with *Monokai Sublime* theme
- Small tweaks for *original* stylesheet

## license

Public Domain or equivalent (CC0 internationally)
