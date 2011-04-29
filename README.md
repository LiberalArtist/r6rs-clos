
# What is this?

Tiny CLOS for R6RS Scheme.

Christian Sloma did the [original conversion](https://code.launchpad.net/~c-sloma/r6rs-clos/r6rs-clos-dev) to R6RS. The Mosh Scheme
team packaged it for Mosh. I ran into some issues in getting Sloma's
original version running. So I tweaked Mosh's version to work with
other implementations. The basic test program [test.sps](https://github.com/dharmatech/clos/blob/master/test.sps) runs in Chez,
Ikarus, and Ypsilon. Ironically, this more portable version doesn't
appear to work with Mosh! :-) I.e. the test program doesn't complete
successfully. Hints on that welcome!

The only dependency is [surfage](https://github.com/dharmatech/surfage).

# Setup

```
$ cd ~/scheme # Where '~/scheme' is the path to your Scheme libraries
$ git clone git://github.com/dharmatech/surfage.git
$ git clone git://github.com/dharmatech/clos.git
```

