Juggernaut-Client
=================

a [Juggernaut](https://github.com/maccman/juggernaut) Client for Browsers

----------------
Installation with [JamJS](http://jamjs.org/) package manager.

    jam install juggernaut

it will install all dependence for you.

```coffee
    define 'package', ['juggernaut'], (Juggernaut)->
      Juggernaut.subscribe 'channel1', (msg)->
        console.log msg
```

