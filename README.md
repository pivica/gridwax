# Gridwax

Fork of original [Gridwax project](https://github.com/itsthatguy/gridwax).

## Intro

Gridwax is very cool, but not very well maintained - so no new features and also lots of bugs are presented currently. Goal of this fork for now is to fix all bugs and do some code cleanup, when this is done we will see what is next ;)

## How to use it

Due to security changes in github it is not any more possible to easily bookmark js code and execute it. For now easy workaround is to use [RawGit service](https://rawgit.com/). So your bookmark URL should look like this

```
javascript:(function()%7Bdocument.body.appendChild(document.createElement('script')).src='http://localhost/pivica/gridwax/gridwax.js';%7D)();
```

## TODO

* Check the code, test, and fix all bugs.
* Remove jQuery dependency.
