# Steps To Reproduce
* `$ git clone git@github.com:tylersamples/snowpack-bug.git # clone repo`
* `$ cd snowpack-bug/assets # change directory to assets`
* `$ npm install`
* `$ npx snowpack dev`
* Observe the error:
```
    [18:53:47] [snowpack] Build Result Error: There was a problem with a file build result.
    [18:53:47] [snowpack] Error: Unexpected: Unscanned package import couldn't be built/resolved.
```