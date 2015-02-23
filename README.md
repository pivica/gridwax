# Gridwax

Fork of a [Gridwax project](https://github.com/itsthatguy/gridwax).

## Intro

Gridwax is very cool, but not very well maintained - so no new features and also lots of bugs are presented currently. Goal of this fork for now is to fix all bugs and do some code cleanup, when this is done we will see what is next ;)

## How to use it

Due to security changes in github it is not any more possible to easily bookmark js code and execute it. For now easy workaround is to use [RawGit service](https://rawgit.com/). So your bookmark URL should look like this

```
javascript:(function()%7Bdocument.body.appendChild(document.createElement('script')).src='https://rawgit.com/pivica/gridwax/master/gridwax.js';%7D)();
```

Gridwax is depending on jQuery for now so you need to preload jQuery on a page on which you want to use this plugin. This limitation will be removed in future and gridwax will not have external dependencies.

## TODO

* Check the code, test, and fix all bugs.
* Remove jQuery dependency.
* Try to use local storage for storing values: vertical align, offset, color.
