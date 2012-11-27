# IntelliJ npm codestyle

Modest attempt creating a set of styling rules in IntelliJ that will match [npm's coding-style](https://npmjs.org/doc/coding-style.html). Although I'm not a big fan of this template, it's getting popular and a lot of developers use it. My take on conventions is that the most important thing is for a team to adhere to the same style, even if it's not concensual or perfect.

## Importing settings

* Download [intellij-npm-codestyle.jar](https://github.com/bitoiu/intellij-npm-codestyle/blob/master/intellij-npm-codestyle.jar)  
* In IntelliJ goto `File - Import Settings` and open the downloaded `intellij-npm-codestyle.jar`
* When IntelliJ restarts goto `Settings/Preferences - Codestyle` and choose `npm-codestyle` from the scheme dropdown.

You now should be able to auto-format and get the closest possible to the npm coding style. Read the current limitations to know where the formatting will not be up to scratch.

## Current limitations

At this point there are a few npm recomendations that cannot be added into IntelliJ 11.1.4. I've started a [discussion](http://devnet.jetbrains.net/thread/440071) on the forums before creating a lot of noise with feature requests, but the goal is to eventually fully match npm's styleguide.

* Comma first is not enforced ( one of the big ones missing )
* Vertically aligning arrays/object elements by the first one
* Removing whitespaces (currently it just doesn't force adding them)
* Adding the whitespaces in 2 specifc scenarios described in the coding-style
